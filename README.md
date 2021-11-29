# Moonlight iOS/tvOS
your powerful desktop computer to your iOS device or Apple TV.

Moonlight also has a [PC client](https://github.com/KnyazQasan/ios15-app-gem/) and [Android client](https://github.com/KnyazQasan/android9+-app-gem/).

Check out [the Moonlight wiki](https://github.com/) for more detailed project information, setup guide, or troubleshooting steps.

[![Moonlight for iOS and tvOS](https://moonlight-stream.org/images/App_Store_Badge_135x40.svg)]

## Building
* Install Xcode 13 from the [App Store page](https://apps.apple.com/us/app/xcode)
* Run `git clone --recursive https://github.com/KnyazQasan/ios15-app-gem/.git`
  *  If you've already clone the repo without `--recursive`, run `git submodule update --init --recursive`
* Open KnyazQasan.project in Xcode
* To run on a real device, you will need to locally modify the signing options:
    * Click on "KnyazQasan" at the top of the left sidebar
    * Click on the "Signing & Capabilities" tab
    * Under "Targets", select "KnyazQasan" (for iOS/iPadOS) or "TV Light" (for tvOS)
    * In the "Team" dropdown, select your name. If your name doesn't appear, you may need to sign into Xcode with your Apple account.
    * Change the "Bundle Identifier" to something different. You can add your name or some random letters to make it unique.
    * Now you can select your Apple device in the top bar as a target and click the Play button to run.
