# LingoPop releases

Downloads for **LingoPop**, a macOS 14+ menu-bar translator. The source code is kept in a separate private repository; this repository only hosts release builds.

**[Download the latest release](https://github.com/nattaponw/lingopop-releases/releases/latest)**

## Install

LingoPop is signed ad-hoc and is not notarized, so macOS will not open a downloaded copy the way it opens a normal app. Clear the download flag once, **before the first open**:

1. Unzip the archive and drag `LingoPop.app` into Applications.
2. Open Terminal and run:

   ```sh
   xattr -dr com.apple.quarantine /Applications/LingoPop.app
   ```

3. Open LingoPop from Applications.

If macOS already showed a Gatekeeper prompt for that copy, `xattr` fails with "Operation not permitted". Delete that copy, unzip the archive again and run step 2 before opening it.

## Use

Press **⌃⌥Space** anywhere to open the window, then **⌘Enter** to run. Add your provider's Base URL, API key and model in Settings. The builds are for Apple silicon (arm64).
