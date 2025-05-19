# 🗺️ Google Map Overlay Android App (Java)

This is a simple Android application built in **Java** that demonstrates how to integrate **Google Maps** using the **Maps SDK for Android**. The app has a main screen with a button that navigates to a map view with a marker.

---

## 📱 Features

- Launch Google Map in a new activity
- Shows a marker at a predefined location (e.g., New Delhi)
- Clean UI with button navigation
- Ready for adding current location or search features

---

## 🚀 Screens

- **MainActivity**: Simple button to open the map.
- **MapsActivity**: Displays Google Map with a marker.

---

## 📦 Project Structure

Google_Map_Overlay/
├── app/
│ ├── src/
│ │ ├── main/
│ │ │ ├── java/com/example/google_map_overlay/
│ │ │ │ ├── MainActivity.java
│ │ │ │ └── MapsActivity.java
│ │ │ ├── res/layout/
│ │ │ │ ├── activity_main.xml
│ │ │ │ └── activity_maps.xml
│ │ │ └── AndroidManifest.xml
│ └── build.gradle


## 🔑 Getting Started

### 1. Clone this Repository

```bash
git clone https://github.com/yourusername/google-map-overlay-android.git
cd google-map-overlay-android
2. Get a Google Maps API Key
Go to Google Cloud Console

Enable Maps SDK for Android

Create an API Key

3. Add API Key to AndroidManifest.xml
xml
Copy
Edit
<meta-data
    android:name="com.google.android.geo.API_KEY"
    android:value="YOUR_API_KEY_HERE"/>
Replace YOUR_API_KEY_HERE with your actual API key.

🛠 Dependencies
Add this line in build.gradle (Module: app):

gradle
implementation 'com.google.android.gms:play-services-maps:18.2.0'
▶️ How to Run
Open the project in Android Studio

Add your API key to the manifest

Click Run ▶️ to launch on a physical/emulator device

🧠 Future Enhancements
Add search functionality using Geocoder

Display current user location

Allow user to drop custom markers

📄 License
MIT License

👨‍💻 Author
Built by Lavish Tembhare
