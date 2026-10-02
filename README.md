# SWTCR

**Your apps, one edge away.**

SWTCR is a lightweight alternative to Stage Manager for switching between the apps you use most. Choose your own apps, move your pointer to the **right edge of the screen**, and pick an app or one of its windows.

It runs in the macOS menu bar, without a Dock icon.

## What you can do

- Choose up to **7 apps** and arrange their order.
- Reveal a panel of large app icons at the right screen edge.
- Switch to an app with a click, or launch it if it is closed.
- Hover over an app to see its window previews and titles.
- Select a window directly, including minimized windows.
- Use the panel on the display where your pointer is located.

The icons stay in place while window previews appear beside them. The panel stays open while you browse and closes when you move away or make a selection.

## Download and install

**Requires macOS 14 Sonoma or later. Works on Apple Silicon and Intel Macs.**

1. Download the DMG from [Releases](https://github.com/damirskenderovic75/SWTCR/releases).
2. Open it and drag **SWTCR** into **Applications**.
3. Launch SWTCR from Applications.
4. In Settings, click **Add Application…** and choose your apps.
5. Arrange them using the up/down buttons.

## Using SWTCR

Hold your pointer at the right screen edge for a moment to open the panel. Hover over an icon to browse windows, then click the icon or a window to switch.

If you cross onto another monitor, the pending activation is cancelled so you can continue moving between displays.

Use the menu-bar icon to open **Settings…** or **Quit SWTCR**.

## Permissions

Basic app switching works without additional permissions. For individual windows, enable these in SWTCR Settings:

| Permission | What it enables |
| --- | --- |
| **Accessibility** | Window titles, selecting windows and restoring minimized windows. |
| **Screen Recording** | Preview images of those windows. |

macOS manages these permissions in **System Settings → Privacy & Security**. After enabling Screen Recording, quit and reopen SWTCR if previews do not appear.

## Privacy

Your app selection stays on your Mac. SWTCR has no accounts or analytics and does not upload window titles or preview images.

Previews are temporary snapshots created when you browse an app. They are held in memory and are not saved as image files.

## A few things to know

- Some windows show a title instead of an image when a preview is unavailable.
- Access to windows on other Spaces depends on macOS and the app.
- SWTCR currently needs to be opened manually after login.
- This is the first release; feedback on multiple monitors and fullscreen apps is welcome.

## Having trouble?

- **No icons?** Add apps in Settings.
- **No panel?** Check that SWTCR is running in the menu bar, then hold your pointer at the right edge.
- **No window titles?** Check Accessibility permission.
- **No preview images?** Check Screen Recording permission and reopen SWTCR.

[Report a problem](https://github.com/damirskenderovic75/SWTCR/issues) with your macOS version, monitor setup and steps to reproduce it.

To uninstall, quit SWTCR and move it from Applications to the Trash.

## License

SWTCR is **free to use for personal and business purposes**. Modification and redistribution require the author's permission. See [LICENSE](LICENSE).
