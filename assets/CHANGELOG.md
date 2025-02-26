## 1.9.0 (2023-04-23)

- feat: directory share
- feat: share via browser link (for non-LocalSend users)
- feat: add "delete from history" button when file could not be opened (by @TheGB0077)
- feat: close message request when copied / opened link
- feat: slightly improve transfer speed
- feat: implement LocalSend protocol v2 with v1 fallback
- feat: scan (sync) button automatically scans all network interfaces when count < 3
- feat(android, ios): add "Save to gallery" setting button in file receive options
- feat(desktop): move troubleshoot out of navigation into send page
- feat(desktop): save last window position (by @TheGB0077)
- feat(android): enable edge-to-edge mode
- feat(android): add monochrome app icons for Android 13 (by @h9419)
- feat(android): set custom download path
- feat(linux): enable system tray (by @TheGB0077)
- fix: in multi-recipient mode, retrying causes a "canceled by sender" on the recipient device
- fix: clear selection after finished message transfer
- fix(ios): could not scan local network on iOS 14+ (by @TheGB0077)
- fix(android, ios): fallback asset picker strings to English translation (by @TheGB0077)
- fix(linux): header bar glitches
- i18n: add fa

## 1.8.0 (2023-03-05)

- feat: add send modes (single recipient, multiple recipients)
- feat: selection gets cleared after finish by default (part of send modes feature)
- feat: share to multiple recipients in parallel
- feat: add troubleshoot page
- feat: add 2 buttons to receive history: open folder + delete history
- feat: cleanup scan UI by hiding multiple network interfaces inside the scan button
- feat: edit text message in selected files
- feat: improve device discovery by answering with TCP instead of UDP
- feat(ex. iOS): pressing destination directory in progress page will open the directory
- feat(android): share apk and install apk
- feat(android): Android TV support
- feat(android): show loading indicator when picking (large) files
- feat(windows): left click on tray icon opens app
- feat(linux): add Control+Q shortcut to exit app
- fix: handshake error in unencrypted mode
- fix: also scan multicast when pressing on a subnet sync button
- fix(android): missing app icon on Android 7
- fix(android,ios): show error message when saving to gallery failed
- i18n: add bn, nl, uk

## 1.7.0 (2023-02-11)

- feat: improve device discovery by enabling multicast
- feat: received files history
- feat: show recent IP addresses in manual IP input
- feat: separate language settings page
- feat: message input is horizontally scrollable when multiline is unselected
- feat: open message normally in QuickSave mode (instead of saving it into a file)
- feat: improve error handling and add possibility to show exact error message for debugging
- feat: add unencrypted HTTP mode (for debugging)
- feat(android): keep file name when saving to photos
- feat(desktop): use bigger default window size if display is big enough
- feat(windows): use "Microsoft YaHei UI" font in Windows which works better with Chinese characters
- fix: cache cleanup on iOS
- i18n: add ar, es-ES, fr-FR, hu, in, it, iw, ja, ko, ne, pl, pt-BR, ru, sv, tr, zh-Hant-HK, zh-Hant-TW (Thanks to all the contributors!)

## 1.6.2 (2023-01-28)

- fix(desktop): close current instance when another is already open
- fix: cannot receive files when Chinese language is active
- fix(android, ios): share files with non-English names

## 1.6.1 (2023-01-27)

- fix(windows): app crashes when minimized to tray
- fix(android, ios): share intent sometimes not working
- fix(android, ios): scan not triggered when coming from share intent
- fix(android, ios): share intent produced duplicates after finishing a transfer

## 1.6.0 (2023-01-27)

- feat: show thumbnail in progress page
- feat: improve cache clearing mechanism
- feat: hashtag input now tries all combinations when multiple subnets are given
- feat(desktop): show dialog instead of bottom sheet when adding files
- feat(windows, mac): minimize to tray
- feat(windows): launch on login
- feat: add multiline toggle to message input
- fix: show correct file count in progress page
- fix: add self-discovering prevention
- i18n: add Simplified Chinese

## 1.5.2 (2023-01-14)

- F-Droid Release

## 1.5.1 (2023-01-10)

- fix(windows): app sometimes crash on start

## 1.5.0 (2023-01-09)

- feat: quick save mode
- feat: accept requests partially
- feat: set destination directory during accept phase
- feat: rename incoming files
- feat: keep screen on during file transfer
- feat: tap to open selected file before sending

## 1.4.0 (2023-01-06)

- feat: support multiple local IP addresses
- feat: detect if message is a link and add a button to open the link

## 1.3.1 (2023-01-03)

- fix: local IP sometimes not found

## 1.3.0 (2023-01-03)

- feat: enter custom target address
- feat: tap to open received file
- feat: responsive UI
- feat(ios): receive share intent
- feat(windows): set destination folder
- fix: update nearby device attributes when scan again

## 1.2.0 (2022-12-31)

- feat: drag and drop files
- feat: share plain messages
- feat(android): receive share intent

## 1.1.0 (2022-12-30)

- feat(android): add media picker
- feat(ios): merge image and video to common media picker
- fix(android): missing internet permission

## 1.0.0 (2022-12-29)

- Initial Release
