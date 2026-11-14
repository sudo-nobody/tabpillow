# Permissions explained

Chrome lists permissions at install time. Here is what each one does and what TabPillow does not do.

| Permission | Why it is needed | What it does not do |
| --- | --- | --- |
| `tabs` | List tabs and suspend inactive ones via `chrome.tabs.discard`. | Does not read page contents or browsing history. |
| `storage` | Keep settings, statistics and workspaces locally. | Does not send data to a cloud. |
| `alarms` | Run sleep checks on a schedule. | No permanent background page; wakes on a timer. |
| `system.memory` | Show free RAM and warn when memory is low. | Does not measure per-tab memory; Chrome has no stable API for that. |
| `notifications` | One low-memory alert. | Rate-limited, not spam. |
| `contextMenus` | A “Keep this tab awake” right-click item. | Does not modify site menus. |

## What TabPillow does not request

- **No host permissions.** It cannot “read and change all your data on all websites”.
- **No content scripts.** It does not inject code into pages.
- **No remote code.** Everything ships inside the extension package.
- **No telemetry or account.** No cloud, no analytics, no browsing-history collection.

Verify in `chrome://extensions` → TabPillow → Details → Permissions.