THE OUMAIMA ARCHIVE — SETUP
===========================

This is a cinematic, interactive birthday website.
The four photos you supplied are embedded directly in index.html.

OPEN LOCALLY
------------
Open index.html in Chrome. The intro envelope, animated sections, photo
lightbox, clickable letters, final reveal, and soundtrack controls work.

ADD THE SPECIFIC SONG
---------------------
You chose a specific song, but haven't told me its title yet.
For now the player is wired to: music/your-song.mp3

To add it:
1. Put an audio file you are allowed to use in the music folder.
2. Name it exactly: your-song.mp3
3. Keep the music folder beside index.html.
4. Click the sound button after opening the archive.

The browser will not autoplay music; she must click to start it.

ADD FRIENDS' PHOTOS
-------------------
Open index.html in a text editor and find:
const memories = [
Add an entry in this format:
{src:"photos/friend-photo.jpg", caption:"A memory with you"}
Put the new image in the photos folder. Keep the file path exact.
You can also replace the sample notes in the section labelled
"Words from your people" with real messages sent by her friends.

PUBLISH FOR A LINK
------------------
Upload index.html, README.txt, the photos folder, and the music folder
to a GitHub repository. Enable GitHub Pages in Settings > Pages:
Deploy from a branch -> main -> /(root).

IMPORTANT
---------
A public GitHub Pages site is visible to anyone with the link (and may be
discoverable). Only upload photos/messages that their owners are happy to
share. Use an audio file you have permission to publish; some commercial
songs may be blocked or muted by hosting platforms.

FINAL PAGE CUSTOMIZATION:
- Open index.html and find [Your name] to replace it with your name.
- The final page reveals 'I love you' in 20 languages, then the letter.
- The music folder is kept by PUT_YOUR_SONG_HERE.txt; add your audio as your-song.mp3.
