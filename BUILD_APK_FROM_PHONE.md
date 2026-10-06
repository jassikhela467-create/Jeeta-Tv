# Build Jeeta TV APK using only an Android phone

This project includes `.github/workflows/build-apk.yml`, so GitHub's cloud computer can compile the app for you.

## 1. Create a GitHub account
Open GitHub in Chrome and sign in/create an account.

## 2. Create a repository
- Tap **+** -> **New repository**.
- Repository name: `JeetaTV`
- Choose **Public** for the easiest free Actions setup.
- Create the repository.

## 3. Upload the project
- Open the new repository.
- Tap **Add file** -> **Upload files**.
- Upload the contents of this ZIP, including the hidden `.github/workflows/build-apk.yml` file.
- Commit the files to the `main` branch.

If your phone's file picker hides `.github`, use GitHub's web editor to create `.github/workflows/build-apk.yml` and paste the workflow from this project.

## 4. Start the cloud build
- Open the repository's **Actions** tab.
- Select **Build Jeeta TV APK**.
- Tap **Run workflow**.
- Select `main` and run it.

A push to `main` also starts the workflow automatically.

## 5. Download the APK
After the workflow shows a green check:
- Open that workflow run.
- Scroll to **Artifacts**.
- Download `JeetaTV-debug-apk`.
- Extract the downloaded ZIP.
- Open the `.apk` file.

## 6. Install
Android may ask you to allow the browser/file manager to install unknown apps. Only enable that permission for the app you trust, install Jeeta TV, and then you can disable the permission again.

## Notes
- The debug APK is signed by Android's debug build system and is suitable for installing/testing on your phone.
- This is a cloud build; your phone does not need Android Studio, the Android SDK, or Gradle.
- Jeeta TV contains no IPTV subscriptions, credentials, or pirated channel lists. Add only services you are authorized to use.
