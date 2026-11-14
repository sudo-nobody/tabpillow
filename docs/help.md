# Help & quick start

## Install

1. Open the Chrome Web Store listing and click **Add to Chrome**.
2. The “Be careful” notice is standard for new extensions — click **Install**.
3. Pick a preset on the welcome page, or skip.
4. Pin the icon via the puzzle menu next to the address bar.

The Chrome Web Store may be blocked in some regions; a VPN may be needed to install. The extension
itself runs locally without a VPN.

## First run

Presets: Gentle (sleep after 60 minutes), Balanced (30), Aggressive (10) and AI Focus. Balanced is a
good default. Everything can be changed later in Settings.

## Suspend tabs

- Open the popup and press **Suspend now**.
- Active, pinned, audible, AI/video and whitelisted tabs stay awake.
- Check tab states in `chrome://discards`.

## AI Focus

Protects ChatGPT, Claude, Gemini, Copilot, Perplexity and other AI sites while the rest sleep sooner.
Auto AI Focus activates when an AI tab is focused.

## Workspaces

Type a name and press **Save** to store the current window. Automatic snapshots are created before
mass suspension and duplicate cleanup.

## Settings and transfer

Timers, whitelist, AI/video protection, notifications and the memory threshold live in Settings.
Export/import JSON moves settings and workspaces to another computer. Settings also sync through
`chrome.storage.sync` when Chrome sync is enabled.

## Tabs do not sleep

1. Check that the tab is not pinned or playing audio.
2. Make sure the site is not whitelisted or protected as AI/video.
3. Press **Suspend now** manually.
4. Check `chrome://discards` and Chrome performance settings.
5. Do not run two tab suspenders at the same time.

## Uninstall

`chrome://extensions` → TabPillow → **Remove**. Chrome deletes local data. Export settings first if
you need a backup.