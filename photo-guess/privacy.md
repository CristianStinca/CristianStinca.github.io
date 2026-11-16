# Photo Guess privacy policy

_Effective: November 16, 2026 (previous version: 2025.10.25)_

Photo Guess is a party game. Everyone's phone joins the **host**: either one player's phone, or an Android TV that everyone watches. In the same room, phones join over Wi-Fi or a phone's hotspot; in an **online game**, players who are apart join the host's phone over the internet, through our relay (see **Online games**). A photo appears on every screen (or, when a TV hosts, on the TV), and everyone guesses whose photo it is. Below, the **host's device** means that phone or that TV.

We built it so that your photos stay with the people you're playing with. We (the developer) never receive your photos, your name or anything about your games. There is no account and no advertising, and the app has no analytics of its own (the one exception is the usage information Google's ML Kit library sends, described under **Google ML Kit**). Our one server is the relay for online games: it passes on encrypted data it can't read and stores nothing.

## The short version

- **Your photos are stored only on the host's device.** The other phones in your game show each photo from memory during its round and never save it; when a TV hosts, the photos show only on the TV and the phones never receive them. Photos are never sent to us, to a cloud service or to any other server in a form anyone else can read: online, they pass through our relay encrypted.
- **They are not backed up.** The host's device keeps the game's photos in a folder that is left out of iCloud and Android backups.
- **They are deleted.** The host's device deletes the photos when the game ends, and clears out anything left over every time the app starts and every time a new game begins.
- **Online games are end-to-end encrypted.** They go through our relay, which can't read your photos, names or games and keeps nothing. It sees only internet addresses, timing and sizes, as any server that passes data on does. See **Online games**.
- **Other players see your photos.** Anyone in your game can see each photo while it's on screen, and could take a screenshot or a picture of the screen. Only add photos you're happy to share with them.
- **Hide faces blurs faces only while people guess.** At the reveal, everyone in the game sees the real photo. Faces are found on your phone and never identified; see **Hide faces**.

## Photos

**What happens to a photo you add.** In **Surprise me**, the default, the app shows you a random grid from your library to review; if the host switches to **Pick them myself**, you choose photos with your phone's own photo picker. Nothing leaves your phone until you confirm. Before sending, your phone shrinks each photo and removes its hidden details (such as location, date and camera model); the host's device removes them again when the photo arrives.

**Where photos are kept.**

1. **Only on the host's device.** Your confirmed photos travel over your local Wi-Fi or hotspot straight to the host's device, and nowhere else. In an online game they travel to the host's phone through our relay, encrypted so that only the host's phone can read them (see **Online games**). Photo Guess contains no analytics, crash-reporting or advertising tools that could receive them.
2. **Other players' phones never save them.** When a round starts, each phone downloads that round's photo from the host and keeps it in memory only, never on its storage, and lets it go after the round. When a TV hosts, the phones download no photo at all: the TV shows it (see **Playing on a TV**).
3. **Not in backups.** On the host's device, game photos are stored in a folder that is excluded from iCloud backup (iPhone and iPad) and from Android's automatic backup, so they can't end up in the cloud that way either.
4. **Deleted.** The host's device deletes all of a game's photos when that game reaches the final scores, when the host ends the game early and when the host closes it. It also deletes everything left in its game folder every time Photo Guess starts and every time a new game starts, so photos from a game that was interrupted (for example if the phone ran out of battery, or the TV was switched off at the wall) are removed the next time the app opens on that device. There is no way to keep the photos after a game.

While a round is on screen everyone in the game can see its photo, just as if you passed your phone around, and anyone could take a screenshot or a picture of the screen; the app can't prevent that. Only add photos you're happy to show the people in your game.

**Surprise me (photo library access).** This is the default mode; the host can switch to **Pick them myself**, which uses your phone's photo picker and never asks for library access. Photo Guess asks to see your photo library only in Surprise me, when your grid is about to be drawn. The random draw happens on your phone; you can shuffle or swap photos, and only the photos you confirm are sent. If you allow only some photos, the app draws from those. On Android, the system may keep small preview thumbnails in the app's private cache while you look through the grid; Photo Guess clears them when you confirm or leave the screen, and, if the app was closed in the middle, the next time you use Surprise me.

## Your name, colour and photo

You type a display name and pick a colour to play. They are kept in the app's memory, sent to the host's device and shown to the other players in the game (and on the TV, when one hosts), and forgotten when you close the app, except for what lets you come back to a game, below. You can also take a photo of yourself as your player picture; see Camera. While you host a game, your phone also announces your name on the local network (as "<your name>'s game") so nearby phones can list the game; it stops when you close the game. A TV announces itself as "TV's game".

**Coming back to a game.** If the app is closed or your phone restarts during a game you joined, Photo Guess can take you back into it as the same player. For that, while you're in the game, your phone keeps one small file holding what it needs to rejoin: your name and colour, whether you joined only to guess, where the game is (the host's local address, or the online game's room and the host's key), the game's join secret or PIN and a token from the host, when it last heard from the host, and, in an online game, the players you blocked and the photos you hid. It never holds a photo or your selfie. The file is left out of iCloud and Android backups, is deleted when you leave the game or the game ends, and is never used more than an hour after your phone last heard from the host. The host's own phone keeps no such file.

## Camera

The camera does two things. It scans the host's QR code to join: nothing is recorded or saved, and those camera pictures never leave your phone.

If you choose **Take a selfie**, it also takes one photo of you as your player picture. This is optional; without it you play with your colour. The photo is cropped small, with its location and camera details removed. The app keeps it in memory only and deletes the camera's temporary copy straight away. It goes only to the host's device, which also keeps it in memory only, and is shown to the players in that game (and on the TV, when one hosts). The host's device drops it when the game closes, and your phone forgets it when you close the app or if the host removes it. On Android the picture is taken by your phone's own camera app, and some camera apps keep their own copy in your gallery; Photo Guess can't control that.

On Android, QR codes are read with Google's ML Kit library (see **Google ML Kit**); joining from the nearby-games list with the 4-digit PIN avoids using the scanner. On iPhone and iPad, QR codes are read with Apple's built-in tools and nothing is sent.

## Holding phones together (NFC)

You can join by holding your phone to the back of the host's phone instead of scanning its QR code. When an Android phone hosts, it passes the game's join link to the phone held against it over NFC, a radio that works only a few centimetres away. A tap passes the join link from phone to phone and nothing else: the same link the QR code shows, with no photo, name or other game data. Nothing is recorded or saved, and the link goes to no one else and to no server. The host's phone offers it only while the app is open with the game's join card or room on screen, the phone is unlocked and the game hasn't started. In the app, an iPhone reads only when you tap **Hold phones together**, and iPhones never pass a link themselves. Outside the app, a phone held to the host's may open the link as it opens any NFC tag: an online invite opens Photo Guess, and a local game's link may open the browser. If NFC is off, or you'd rather not use it, scan the code or use the PIN as before.

## Hide faces

The host can turn on **Hide faces** for a game. A face gives a photo away at a glance, so in this mode faces are blurred while everyone guesses, to make the game fairer. It is off unless the host turns it on.

- **Faces are found on your phone.** When you add photos to a Hide faces game, your phone looks for faces in each photo and blurs them, using Google's ML Kit library on your phone (see **Google ML Kit**). It only finds where faces are in the picture: it never works out whose face it is, and it does not use faces to identify anyone. The face positions are used to blur that photo and then forgotten; no face data is stored, sent to any server or kept anywhere.
- **Two versions go to the host's device.** For a photo with a face in it, your phone sends two versions over your local network (or, in an online game, through our relay, encrypted) to the host's device, like any game photo: the blurred one and the unblurred one. A photo with no face found is sent once, as usual. Before you confirm, your phone shows you the photos blurred as they will be sent, so you can swap out any photo where a face was missed.
- **Everyone sees the unblurred photo at the reveal.** Players guess with the blurred photo; when the answer is revealed, every player in the game sees the photo unblurred (on the TV, when one hosts). Hide faces is there to make guessing fair, not to keep faces from the other players: only add photos you're happy for everyone in the game to see unblurred.
- **Kept and deleted like any game photo.** The host's device stores both versions in its game folder, which is left out of backups, and lets other phones download the unblurred one only while that photo's answer is on screen (when a TV hosts, no phone downloads either version). The other phones keep it in memory only. Both versions are deleted when the game ends, or earlier if the photo is removed, exactly as described under **Photos**.

## Playing on a TV

An Android TV (or Google TV) can host a game that everyone watches. The TV only hosts: it is not a player, has no player name or picture (it shows up as "TV's game" in the nearby list), and never joins a game.

- **Photos go to the TV and show only there.** Each phone sends its confirmed photos over your local network to the TV, like to a host's phone. The TV shows each round's photo; the phones in a TV game never receive or download a round's photo, the unblurred version included. Players answer on their phones.
- **Kept and deleted on the TV.** The TV stores the game's photos in the app's game folder, which is left out of Android's backups. It deletes them when the game reaches the final scores, when the game is ended and when it is closed. If the app on the TV was stopped in the middle of a game (for example, the TV was switched off at the wall), the TV deletes them the next time Photo Guess starts on it: on a shared TV that may be a while, so end the game before switching the TV off.
- **Nothing else changes.** Player pictures and names go to the TV and the phones as in any game, in memory only. The TV never uses a camera, never scans a code and never looks for faces: Hide faces is done on each player's phone, as above.

## Google ML Kit

Photo Guess uses Google's ML Kit library in two places: on Android, to read the host's QR code; and on Android, iPhone and iPad, to find faces in a **Hide faces** game. ML Kit runs on your phone. Under Google's terms, the images it looks at and what it finds in them are processed on the device and are not sent to Google (<https://developers.google.com/ml-kit/terms>): no camera images, photos, faces, names or game content.

The library does send Google its own usage and performance information: the device model and system version, the app's name and version, a per-installation identifier, performance figures (such as how long finding faces took), settings (such as the image size and format), which ML Kit features were used, and error codes. Google uses this for diagnostics and usage analytics. For Android, Google says it encrypts this in transit and does not pass it to third parties. ML Kit may also contact Google from time to time to receive updates to the library. Google lists this information at <https://developers.google.com/ml-kit/android-data-disclosure> (Android) and <https://developers.google.com/ml-kit/ios-data-disclosure> (iPhone and iPad).

This happens mainly when ML Kit is used: on Android when you scan a QR code, and on any phone when it looks for faces in your photos in a Hide faces game. On Android, ML Kit also starts up when the app opens. An Android TV never scans a code or looks for faces, but the same app runs there, so ML Kit starts up when the app opens on a TV too.

## Online games

The host can choose **Host online** to play with people who aren't in the room. Online games work like games on a Wi-Fi, with these differences.

- **Through our relay, end-to-end encrypted.** The host's phone still runs the game and holds the photos. The other phones reach it through our relay, a server we run at photoguess.online. Each phone's connection to the host's phone is end-to-end encrypted (the Noise protocol, with keys made fresh for each game and kept in memory only), so the relay passes on data it can't read: no photos, names, answers or scores.
- **What the relay sees.** Like any server that data passes through, the relay sees the internet (IP) addresses of the phones connected to it, when they connect, and how much data they send. It holds addresses in memory only: while a phone is connected, and for about a minute afterwards, to limit how often one address can open games or look up room codes. It keeps no record of who connected or played and writes nothing to disk: its service log notes only that a room opened or ended, with the number of rooms open, and nothing about who was in it. When a game ends, nothing about it is left on the relay. Someone who could watch the relay could guess from the sizes which phone sent a photo, but not what is in it.
- **Who can join.** Players join with the host's invite link (or its QR code), or with the game's room code and PIN. The secret part of an invite link sits after the `#`, which browsers and link previews never send to any server. The host sees each request with the player's name and colour (never their selfie) and lets them in or declines. A PIN join shows a 6-digit check code on both phones, so the host can tell no one sat in the middle.
- **Smaller photos.** Online, photos are shrunk further before they're sent (at most 1024 pixels and about 200 KB each). A 12-player game with the default settings uses up to about 95 MB of mobile data on the host's phone and 9 MB on each other phone, about twice that with **Hide faces**; the invite card shows the figure for your game.
- **TV games are local only.** A TV never hosts an online game.

**Community rules.** Before your first online game, whether you host or join, the app shows our community rules (published at <https://cristianstinca.github.io/photo-guess/rules>) and goes on only if you accept them. Your phone then keeps one small file that records which version you accepted, nothing else (it may be in your phone's backups, like other app settings); it asks again when the rules change.

**Report.** In an online game, you can report the photo on screen, or a player from the player list. The app then opens your own mail app with a draft to cristianstinca.support@gmail.com that says only the reason, what was reported (a photo or a player), "online game", the app version and the platform: no photo, name, room code, invite, PIN or other game data. You decide whether to send it, and you may add a screenshot or a message. If you send it, we receive your email, with your email address and anything you added, and use it only to answer your report. We keep it for up to a year after the report is answered, then delete it. We can't see games or photos, so we can't remove anything from someone's phone: our answer can explain the tools in the app and, for anything illegal, point you to the police. Reporting a photo also hides it on your phone.

**Block.** Blocking a player hides their player picture on your phone at once, and their photos from each answer reveal on, for the rest of that game. Nothing is sent: no one, the host included, is told.

## Playing from a browser on the Wi-Fi

Someone without the app can join a game on the same Wi-Fi from a web browser: the host's device (a phone or a TV) shows a link and a QR code that open the game's web page, served by the host's device itself over the local network, and by nothing else. The page asks for the host's PIN, or uses the link's secret, then plays like the app. The browser keeps only your name and colour in its local storage and, while you're in a game, what it needs to rejoin it (as under **Coming back to a game**) in that tab's session storage, which the browser clears when the tab closes. It stores no photo, cookie or anything else, and the page loads nothing from any other server. The community rules, Report and Block are for online games and don't appear in these local games.

## The local network

In a game on your Wi-Fi or hotspot, the phones, and the TV when one hosts, talk to each other directly over that network. Nothing goes over the internet. Joining needs the secret in the host's QR code or the host's 4-digit PIN. This local connection is not encrypted (online games are, see above), so, as with anything on a shared Wi-Fi, someone else on the same network with the right tools could in principle see what passes between the devices; play on a network you trust, or on a phone's hotspot.

## What we collect

We collect nothing from the app. Our only server, the relay for online games, passes on encrypted data it can't read and keeps nothing (see **Online games**). Apart from Google ML Kit's usage information described under **Google ML Kit**, the app sends nothing to anyone outside your game. The one thing that can reach us is a report you choose to email us (see **Report**).

- No accounts or sign-in.
- No record on the relay of who played or with whom: its log notes only that a room opened or ended.
- No advertising, no tracking across apps or websites, no selling or sharing of data.
- No analytics or crash reporting of our own; Google ML Kit's usage information (above) is the only exception.
- No face recognition: Hide faces only finds where faces are, to blur them, and keeps no face data.

## Children

Photo Guess is a general-audience party game, not directed at children. We collect no personal information, from children or anyone else; the only data that leaves the phone for anyone outside the game is Google ML Kit's usage information described above, which includes a per-installation identifier, and, in an online game, the encrypted traffic our relay passes on (see **Online games**). Online games are with people who may not be in the room: younger players should play online only with people they know, with an adult who hosts.

## Your choices

- Choose which photos to add, remove them before the game starts, and leave a game at any time.
- Play only on your Wi-Fi or a TV, and nothing goes over the internet; decline the community rules and the app doesn't go online.
- In an online game, report a photo or a player, and block a player on your phone.
- Deny camera access, join with the PIN and play with a colour; deny photo-library access and pick photos yourself.
- As host, leave **Hide faces** off; as a player, swap out any photo you don't want everyone to see unblurred at the reveal.
- Deleting the app deletes everything it stored on your phone.

Because we hold no data about you, there is nothing for us to access, export or delete on request, except a report email you sent us, which we delete if you ask.

## Changes

If this policy changes, the new version will be posted at this address with a new effective date.

## Contact

Questions and reports: cristianstinca.support@gmail.com
Developer: Cristian Stinca
