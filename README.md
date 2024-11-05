# Remove-Quarantine-Bit-Quick-Action
An automator quick action for removing the quarantine bit on un-notarized Mac apps.

It's super simple. It just runs the command `xattr -d com.apple.quarantine` on all selected files and then either displays a notification if successful or an error dialog if it fails.

![A screenshot of the context menu item belonging to this quick action](screenshot.png)

To install, just copy `Remove Quarantine Bit.workflow` to `/Users/<username>/Library/Services/`. After that, you should see a new item under "Quick Actions" in the context menu opened by right-clicking applications.