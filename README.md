# Forum History — tester downloads

Two macOS apps that show data already stored on your Mac. Nothing leaves your Mac: no account, no network calls, no analytics.

| App | Shows |
| --- | --- |
| **Forum History** | Your Google Chrome browsing history (all profiles) |
| **Forum History Plus** | Chrome history, plus your Apple Messages and call history |

Downloads: see [Releases](../../releases). Requires **macOS 13 (Ventura) or later**, Apple silicon or Intel.

## ⚠️ These are unsigned development builds

They are not yet signed or notarized by Apple, so macOS will block the first launch. To open them:

1. Open the downloaded `.dmg` and drag the app onto the **Applications** shortcut.
2. Open the app from **Applications**. macOS says it can't verify the developer. Click **Done**.
3. Go to **System Settings › Privacy & Security**, scroll down, and click **Open Anyway** next to the app's name. Confirm with your password.

You'll need to repeat this for each new build.

## Forum History Plus: Full Disk Access

macOS protects Messages and call history. The first time you click **Show my history, messages, and calls**, your Chrome history appears right away, and the Messages and Calls tabs show an **Open Full Disk Access Settings** button:

1. Click the button. If prompted, first click **Move to Applications and Reopen**.
2. Turn on **Forum History Plus** in the list. If it isn't listed, click **+**, choose Applications › Forum History Plus, and click Open.
3. If macOS asks, choose **Quit & Reopen**. The app picks up where it left off.

Manual path: System Settings › Privacy & Security › Full Disk Access.

Development builds lose this permission whenever you install a new build. Remove the old entry and turn it on again.

## Feedback

Please report how many steps it took from opening the app to seeing your data, anything confusing, and any data that looks wrong or missing. Please don't send screenshots of your messages or history.
