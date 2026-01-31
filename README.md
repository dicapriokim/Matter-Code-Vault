Matter Code Vault
Matter Device Management & QR Code Backup/Restore Tool (v2.22.7)

Matter Code Vault is a powerful Home Assistant add-on designed for seamless Matter device management. Securely back up complex pairing codes and QR codes, and manage them intelligently using AI-driven features.

✨ Features
1. Structured Classification System (Setup) Organize your data by pre-defining installation locations, manufacturers, platforms, and device types. Build a clean, typo-free library simply by selecting pre-registered tags.

2. Smart Device Registration Register devices by scanning QR codes via PC webcam or mobile camera, or by uploading photos from your gallery. Google Gemini AI analyzes device information to automatically recommend the most appropriate names.

3. Intelligent VID Management Automatically analyze and learn the Vendor ID (VID) of Matter devices. Even for manufacturers not on the official list, you can manually add or edit mapping information for perfect management.

4. Intuitive Main UI & Dynamic Filtering Find devices using natural language queries via AI or utilize powerful search and filter functions. The Automatic Location Filtering feature hides empty locations, and you can reorder rooms with a simple drag-and-drop.

5. QR Image Generation & Labeling Re-generate high-quality QR code images from your stored data. Download images optimized for label printers to attach to physical devices for easy re-pairing anytime.

6. Seamless Backup & Restore Export or import your precious device data as JSON files. Restore your data safely without fear of loss, even after a fresh Home Assistant reinstallation.

7. Creator Mode (🛡️) Designed with YouTubers and bloggers in mind. 'Creator Mode' precisely masks sensitive QR codes and pairing digits, allowing you to share your screen with confidence.

🚀 How to Install (Add Repository)
Install this add-on by adding the repository to your Home Assistant Add-on Store.

Navigate to Home Assistant Settings > Add-ons > Add-on Store.

Click the Menu (3 dots) in the top right corner > Repositories.

Enter the following URL and click Add:

Plaintext
https://github.com/dicapriokim/Matter-Code-Vault
Find Matter Code Vault in the list and click Install.

⚠️ Important Notes
Data Storage: This app stores data locally in the /data/matter_data.json file within Home Assistant. Since deleting the add-on may also remove this data, always use the backup feature to keep a copy on your PC.

Camera Permissions: Due to browser security policies, the camera only functions in HTTPS or localhost (127.0.0.1) environments. When accessing via HTTP externally, please use the 'Photo Album' upload feature.

Integrity Verification: The app verifies code integrity upon startup. If an "Unauthorized modification detected" warning appears, the app will be disabled. Please do not modify the core files.

Designed by 돼지지렁이
