# FloatOver

Keep any app floating on top of whatever is fullscreen on your **Windows** PC, the way floating windows work on Android. Watch something fullscreen and keep a chat, a chart or your notes in the corner.

### [⬇ Download FloatOver](../../releases/latest)

Get `FloatOver-Setup-<version>.exe` from the latest release. It installs for just your user, with no admin prompt and no account. Prefer not to install anything? `FloatOver.exe` on the same page runs as it is.

---

## What it does

- **Floats any open window.** Open FloatOver and click **Float** next to an app, or press **Ctrl+Alt+F** over anything and pick one. The app shrinks into the top-right corner and stays on top of the fullscreen app underneath.
- **It's the real app,** not a picture of it. Click, type and scroll in it as usual.
- **Pops videos out.** Float a browser that's playing a video and just the video comes out, in the browser's own picture-in-picture player, on top of everything. The browser minimises. The video can be in any tab. Chrome-family browsers need a free extension from Google; the installer can add it for you (see below). Firefox needs nothing.
- **A ••• handle** sits above each floating window. Drag it to move the window. Click it for **Full screen**, **Minimise** or **Close**. Close puts the window back to the size and place it had before.
- **Minimise to a bubble.** A minimised floating window becomes a bubble with its app's icon on the screen edge. After 3 seconds it tucks half away. Hover to bring it out, click to open the window again, or drag it to the left or right edge.
- **Starts with Windows** if you want it to, which is the default. Turn it off in FloatOver, or in Task Manager's Startup apps; the two stay in sync.
- **Never traps you.** Maximize a floating window and it stops floating, so other apps and tray pop-ups can come in front again. Quitting FloatOver puts every window back the way it was.

## Privacy

FloatOver never goes online: no accounts, no servers, no telemetry, no update checks. It moves and resizes windows on your PC, and presses keys in your browser to reach a playing video's tab and pop the video out. To find a playing video it reads the title Windows shows in its media controls, and that title stays on your PC.

If you leave the extension option ticked in the installer, it tells Chrome and Brave where to find Google's Picture-in-Picture extension, and they download it from the Chrome Web Store themselves.

## Getting started

1. Run `FloatOver-Setup-<version>.exe`. Windows may show **"Windows protected your PC"**. That's SmartScreen flagging a new app that isn't signed, not a virus. Click **More info → Run anyway**. If you watch videos in Chrome or Brave, leave **Add Google's free Picture-in-Picture extension** ticked. Your browser then asks whether to turn the extension on. Click **Enable**, or videos won't pop out. Missed it, or use Edge? Open FloatOver and use the **Video pop-out** buttons, which open the extension's page in your browser.
2. The FloatOver window opens when setup finishes. Next time, open it from the Start menu, or click the tray icon and choose **Open FloatOver**. If you don't see the tray icon, click the **^** next to the clock.
3. Open something fullscreen, press **Ctrl+Alt+F**, and pick the app you want floating.

To remove it, go to **Settings → Apps → Installed apps → FloatOver → Uninstall**.

## Known limits

- Games aren't supported yet. That's the next thing being worked on.
- Apps running as administrator, like Task Manager, can only be floated if FloatOver runs as administrator too.
- Some apps won't shrink below their own minimum size, so they float a bit bigger.
- The installer adds the video extension to Chrome and Brave only. For Edge, use the button in FloatOver. For Opera or Vivaldi, add [Picture-in-Picture Extension (by Google)](https://chromewebstore.google.com/detail/picture-in-picture-extens/hkgfoiooedgoejojocmhlaklaeopbecg) from the Chrome Web Store yourself.
- A video pops out only if it shows up in Windows' media controls, the panel the volume keys bring up. If it doesn't, the whole browser window floats instead.
- The video pop-out has only been tried with browsers in English.

## Requirements

Windows 11, 64-bit. Windows 10 should work too, but hasn't been tested yet.

---

*Free. An early version, so expect rough edges. No warranty.*
