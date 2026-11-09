# Caffeine

This fork is based on the [original Caffeine repository](https://github.com/domzilla/Caffeine). The only difference is the app icons; everything else is the same as the original project.

## Download a build

1. Open the [Actions tab](https://github.com/patopitaluga/Caffeine/actions).
2. Select a successful **Build** run for the branch or pull request you want.
3. Under **Artifacts**, download **caffeine-macos**.
4. Unzip the download. It should contain `Caffeine.app`; move it to your Applications folder.

The workflow runs on pushes and pull requests. Builds are unsigned and are retained by GitHub Actions for a limited time.

## “Caffeine.app” Not Opened

The GitHub Actions build is not signed or notarized, so macOS may say it could not verify that `Caffeine.app` is free of malware. Only bypass this warning if you downloaded the app from this repository and trust its contents.

To open it:

1. Try to open `Caffeine.app` and dismiss the warning.
2. Open **Apple menu > System Settings > Privacy & Security**.
3. Scroll to **Security** and click **Open Anyway** next to the message about Caffeine.
4. Confirm that you want to open the app and authenticate if prompted.

If **Open Anyway** is not shown, try opening the app once more and check Privacy & Security again.
