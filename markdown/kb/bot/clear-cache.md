# Clearing Discord Cache – Web, Desktop, and Mobile

This guide explains how to clear Discord’s cache on **web**, **desktop** (Windows & macOS), and **mobile** (Android & iOS).  
Clearing the cache can help fix glitches, loading issues, and free up storage.

---

## 🖥 Web (Browser Version)

1. Open your browser’s **Settings** or **History** menu.  
   ![Browser settings](images/web_settings.png)

2. Find **“Clear browsing data”** or **“Clear cache”**.  
   ![Clear browsing data option](images/web_clear_data.png)

3. Select only **“Cached images and files”**.

4. Click **Clear data**.  
   *(This removes temporary site data but keeps your logins.)*  
   ![Clear cache confirmation](images/web_confirm_clear.png)

---

## 💻 Desktop App

### **Windows**
1. Close Discord completely.  
   *(Right-click in the taskbar → Quit Discord)*  
   ![Quit Discord](https://cdn.halloweenbot.com/images/screenshots/kb/windows_quit_discord.png)

2. Press **Win + R**, type:
    ``%appdata%\discord``
    and press **Enter**.  
![Run appdata](https://cdn.halloweenbot.com/images/screenshots/kb/windows_appdata_run.png)

3. Delete these folders:
- `Cache`
- `Code Cache`
- `GPUCache`  
![Delete cache folders](https://cdn.halloweenbot.com/images/screenshots/kb/windows_delete_folders.png)

4. Empty your Recycle Bin.

---

### **macOS**
1. Quit Discord fully.  
*(Right-click the icon in the Dock → Quit)*  
![Quit Discord Mac](images/macos_quit_discord.png)

2. In Finder, click **Go → Go to Folder…**, and type:
   ``~/Library/Application Support/discord/``
![Go to folder](images/macos_goto_folder.png)

3. Delete:
- `Cache`
- `Code Cache`
- `GPUCache`  
![Delete cache Mac](images/macos_delete_folders.png)

4. Empty your Trash.

---

## 📱 Mobile

### **Android**
1. Open **Settings → Apps → Discord → Storage**.  
![Android Discord settings](images/android_app_settings.png)

2. Tap **Clear Cache**.  
*(This keeps your login and settings.)*  
![Android clear cache](images/android_clear_cache.png)

---

### **iOS (iPhone/iPad)**

#### Option A – Offload App
1. Go to **Settings → General → iPhone Storage → Discord**.  
![iOS app storage](images/ios_app_storage.png)

2. Tap **Offload App**.  
![iOS offload](images/ios_offload.png)

3. Tap **Reinstall App**.

---

#### Option B – Delete & Reinstall
1. Long-press the Discord icon → **Remove App → Delete App**.  
![Delete app iOS](images/ios_delete_app.png)

2. Reinstall Discord from the App Store.

---

## 📊 Summary Table

| Platform    | Steps                                                                 |
|-------------|----------------------------------------------------------------------|
| **Web**     | Clear cache from browser settings.                                   |
| **Windows** | Delete `Cache`, `Code Cache`, and `GPUCache` from `%appdata%\discord`|
| **macOS**   | Delete same cache folders from `~/Library/Application Support/discord/`|
| **Android** | App Settings → Storage → **Clear Cache**.                            |
| **iOS**     | Offload or Delete & Reinstall the app.                               |

---

## 💡 Why Clear the Cache?
- Frees up storage space.
- Fixes image loading or lag issues.
- Resolves some app glitches without deleting your data.
