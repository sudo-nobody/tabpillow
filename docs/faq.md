# FAQ

### Does TabPillow collect data?
No. The extension has no analytics, telemetry, account or cloud. Settings and statistics stay in
`chrome.storage`; browsing history is never read.

### Is tab suspension safe?
Yes. It uses Chrome's native `discard`. Titles, favicons, groups and scroll position are preserved;
clicking a sleeping tab reloads it in place.

### Will I be logged out?
No. Suspension does not delete cookies. Logins stay.

### Why did YouTube reload?
Chrome or another suspender discarded the tab. Enable “Never suspend YouTube and video” in
TabPillow, or add youtube.com to Memory Saver exceptions.

### Does it work alongside Chrome Memory Saver?
Yes, but do not run both blindly. Turn one off or mirror the exceptions, otherwise they may compete
for the same tabs.

### Why does Chrome show a warning during install?
It is Chrome's standard notice for new extensions with Enhanced Safe Browsing. TabPillow uses no
remote code and collects no data; click **Install**.

### Does TabPillow work in Russia without a VPN?
The extension itself runs in Chrome without a VPN. The Chrome Web Store is blocked in Russia, so a
VPN may be required to install it.

### How do I move settings to another computer?
Export settings to JSON in Settings and import them on the other device. Settings also sync via
`chrome.storage.sync` if Chrome sync is enabled.

### How do I uninstall and delete data?
`chrome://extensions` → TabPillow → Remove. Chrome deletes local extension data.