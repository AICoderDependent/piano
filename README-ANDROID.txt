PIANO PRACTICE ON ANDROID - install it once, use it any time

What this does: puts the app on your phone's home screen like a normal app. After the
first visit it also opens without internet. The piano connection works because the app
is served from a secure web address.

STEP 1 - Put the files online (once, free, about 10 minutes, on your computer)
1. Go to github.com and create a free account.
2. Click New repository. Name it "piano". Leave it Public. Click Create repository.
3. Click "uploading an existing file". Drag in ALL of these files (not the zip):
     index.html
     manifest.webmanifest
     sw.js
     icon-192.png
     icon-512.png
     icon-512-maskable.png
   Click Commit changes.
4. Open Settings > Pages. Under "Build and deployment" choose Deploy from a branch,
   pick the "main" branch and the "/ (root)" folder, then Save.
5. Wait a minute or two. The page shows your address, like
   https://yourname.github.io/piano/
   (The page is public. Your MIDI files are not uploaded anywhere. They stay on the phone.)

STEP 2 - Install it on the phone
1. Open that address in Chrome on the phone (once, with internet).
2. Tap the three dots (top right), then "Install app" (or "Add to Home screen").
3. The Piano icon appears on your home screen. Open it from there from now on.

STEP 3 - Connect the piano
1. Switch the piano off. Connect it to the phone with a USB-C to USB-B cable
   (or a USB-A to B cable plus a USB-C adapter), into the piano's USB TO HOST socket.
2. Switch the piano on, open the app, and tap the piano status at the top.
3. Allow the MIDI and USB permission prompts.

Updating later: if you upload a new index.html, also open sw.js and change
'piano-practice-v1' to 'piano-practice-v2' (and so on), so the phone fetches the new version.

Not working? Make sure you opened it in Chrome, from the https address (not from the
Downloads folder), and that the piano was switched on after the cable was connected.
