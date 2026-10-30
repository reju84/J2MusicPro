# J2 Music Pro — Ultra-Lightweight Android App for Samsung Galaxy J2 (2016)

## Key Features Included
- **Ultra-Lightweight Native Architecture**: Supports `minSdk 21` (Android 5.0 Lollipop & Android 6.0.1 Marshmallow on Galaxy J2 2016) with under 2.5 MB APK size and minimal RAM usage.
- **Pure Black (`#000000`) Super AMOLED Dark Mode**: Saves battery on Samsung Galaxy J2's Super AMOLED display.
- **100% English Menu Interface**: Clean English tabs (`Songs`, `Folders`, `Playlists`, `Radio`, `YT Audio`).
- **Folder View & Local Scanner**: Automatically groups songs from Internal Storage and External MicroSD card by folder.
- **Custom Playlists & Favorites**: One-tap `★ Favorites` and custom playlist builder stored locally.
- **Sleep Timer with Gentle Volume Fade**: Set `15m`, `30m`, `45m`, `60m`, or `Stop After Current Song Ends`.
- **Online Radio & Live Stream Player**: Built-in Bangla, Bollywood, Lofi, Retro FM streams + Custom Stream URL player.
- **YouTube Link Audio-Only Downloader**: Paste any YouTube link (or share directly from the YouTube app to J2 Music Pro) to extract and download **Audio Only (`.m4a` / `.mp3`)** directly into `/Music/J2MusicPro/` using Android's native `DownloadManager`.
- **Hardware 5-Band Equalizer & Bass Boost**: Native hardware audio effects + headphone unplug auto-pause.

## How to Build the `.APK` File (2 Easy Ways)

### Method 1: Build in Android Studio (PC / Laptop)
1. Extract `J2MusicPro_Android_Project.zip`.
2. Open **Android Studio** -> **Open** -> Select the extracted `J2MusicPro` folder.
3. Wait for Gradle Sync to finish, then click **Build -> Build Bundle(s) / APK(s) -> Build APK(s)**.
4. Copy `app/build/outputs/apk/debug/app-debug.apk` to your Samsung Galaxy J2 and install!

### Method 2: Build Online for Free Without PC (GitHub Actions)
1. Create a free repository on GitHub and upload the files from `J2MusicPro_Android_Project.zip`.
2. Go to the **Actions** tab in your GitHub repository — the included `.github/workflows/build-apk.yml` workflow will automatically compile the project and give you the downloadable **`J2MusicPro-APK`**!
