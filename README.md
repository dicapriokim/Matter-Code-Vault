Matter Code Vault
Matter Device Management & QR Code Backup/Restore Tool (v2.22.7)

Matter Code Vault is a powerful Home Assistant add-on designed for seamless Matter device management. Securely back up complex pairing codes and QR codes, and manage them intelligently using AI-driven features.

✨ Key Features
Smart Registration: Scan via webcam, upload photos, or manual input with AI-powered name recommendations via Google Gemini.

Dynamic UI: Auto-hides empty locations and supports drag-and-drop sorting for a clean workspace.

VID Management: Automatically identifies and learns Manufacturer Vendor IDs from QR payloads.

Creator Mode (🛡️): Precisely masks sensitive QR/pairing codes for safe screen sharing or streaming.

Label Ready: Generate and download high-quality QR images optimized for label printers.

📖 Quick Start Guide
1. Initial Setup
Before adding devices, define your ecosystem in the [Settings ⚙️] menu to prevent data fragmentation:

Locations: Living Room, Bedroom, Entrance, etc.

Manufacturers: Aqara, Eve, Nanoleaf, etc.

Platforms: Apple Home, SmartThings, Home Assistant, etc.

2. Adding a Device
Click the [+] button. You can use your camera or upload a photo.

AI Suggestion: Click the 'Magic Wand' icon to get the best name based on device type and location.

Manual Entry: Ensure the pairing code is entered as an 11-digit number without hyphens or spaces.

3. Exploring the Main UI
AI Chat: Use the 'Ask AI' button for natural language queries about your devices or app usage.

Status Badges:

🔵 Blue: Full MT Payload (Raw Data) included.

🔴 Red: Pairing code only (Payload missing).

Sorting: Grab the [:::] handle on location headers to reorder your dashboard.

⚙️ Configuration & API Key
To enable AI features, you need a Google Gemini API Key:

Go to HA Settings > Add-ons > Matter Code Vault > Configuration tab.

Paste your key in the api_key field.

Note: Core features (registration, backup, etc.) work perfectly even without an API key.

🚀 How to Install
Go to Add-ons > Add-on Store in Home Assistant.

Select Repositories from the top-right menu.

Add: https://github.com/dicapriokim/Matter-Code-Vault

Find Matter Code Vault and click Install.

⚠️ Important Notes
Data Safety: Data is stored locally at /data/matter_data.json. Always export a JSON backup before deleting the add-on to prevent data loss.

Camera Access: Due to security policies, the camera requires HTTPS or localhost. Use 'Photo Upload' for remote HTTP access.

Integrity Check: Any unauthorized modification will trigger an integrity alert, disabling the app.

Designed by 돼지지렁이
