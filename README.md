# PStream iOS App

A native iOS wrapper for zstream.mov — full-screen, supports video playback and Picture-in-Picture.

---

## How to Build Your IPA

### Requirements
- A Mac running macOS 13 or later
- Xcode 15 (free from the Mac App Store)
- A free Apple ID (no paid developer account needed for personal use)

---

### Step 1 — Open in Xcode
1. Unzip the project folder
2. Double-click **PStream.xcodeproj** to open it in Xcode

### Step 2 — Sign in with your Apple ID
1. In Xcode, go to **Xcode → Settings → Accounts**
2. Click **+** and sign in with your Apple ID
3. Close Settings

### Step 3 — Set your Team
1. Click **PStream** in the left sidebar (the blue icon at the top)
2. Select the **PStream** target
3. Under **Signing & Capabilities**, set **Team** to your Apple ID name

### Step 4 — Build the Archive
1. In the top menu: **Product → Destination → Any iOS Device (arm64)**
2. Then: **Product → Archive**
3. Wait for the build to finish (1–2 minutes)

### Step 5 — Export the IPA
1. The **Organizer** window will open automatically
2. Click **Distribute App**
3. Choose **Custom** → **Direct Distribution**
4. Click **Distribute** → Save the IPA to your Desktop

✅ You now have a signed IPA ready to install via AltStore, Sideloadly, or any sideloading tool.

---

## App Features
- Full-screen WebView wrapping https://zstream.mov
- Inline video playback (no forced fullscreen pop-up)
- Picture-in-Picture support
- Portrait + Landscape orientation
- Dark background matching the site theme
- Back/forward swipe navigation
