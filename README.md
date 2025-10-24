# 🎧 Openwhyd Music App

A beautiful **React Native music app** powered by the [Openwhyd API](https://openwhyd.org/), allowing users to explore and listen to trending tracks, browse playlists, and discover new music genres.

---

## 🚀 Features

* 🎵 **Explore Hot Tracks:** Fetch the latest trending songs via Openwhyd API.
* 🎬 **Movie & Song Tabs:** Navigate seamlessly between Movies and Songs.
* 📱 **Dynamic Navigation:** Built with React Navigation and TypeScript.
* 💫 **Modern UI:** Clean, minimal, and responsive interface for an engaging experience.
* 🔍 **Detailed View:** Tap any item to see details like title, artist, and cover art.

---

## 🛠️ Tech Stack

| Category          | Technology                            |
| ----------------- | ------------------------------------- |
| **Framework**     | React Native                          |
| **Navigation**    | React Navigation (Stack & Tabs)       |
| **Language**      | TypeScript                            |
| **Data Source**   | Openwhyd Public API                   |
| **UI Components** | React Native Elements / Custom Styles |

---

## ⚙️ Installation

1. **Clone this repository**

   ```bash
   git clone https://github.com/username/openwhyd-music-app.git
   cd openwhyd-music-app
   ```

2. **Install dependencies**

   ```bash
   npm install
   ```

3. **Run the app**

   ```bash
   npm start
   ```

   or using Expo:

   ```bash
   expo start
   ```

---

## 🔗 API Reference

All song data is fetched from Openwhyd’s public API:

```
https://openwhyd.org/hot/electro?format=json
```

This endpoint returns trending tracks from the *Electro* category in JSON format.

You can replace `electro` with any genre (e.g. `pop`, `rock`, `hiphop`).

---

## 📸 Screenshots

<p align="center">
   <img src="[assets/screenshots/detail.png](https://github.com/Ranggis/TUGAS-PEMROGRAMAN-PERANGKAT-MOBILE-SESI-6/blob/main/Hasil%20Implementasi/Movie%20List.jpg)" width="45%" />
  <img src="https://github.com/Ranggis/TUGAS-PEMROGRAMAN-PERANGKAT-MOBILE-SESI-6/blob/main/Hasil%20Implementasi/Movie%20Detail.jpg" width="45%" />
</p>
<p align="center">
  <img src="[assets/screenshots/list.png](https://github.com/Ranggis/TUGAS-PEMROGRAMAN-PERANGKAT-MOBILE-SESI-6/blob/main/Hasil%20Implementasi/Song%20List.jpg)" width="45%" />
  <img src="https://github.com/Ranggis/TUGAS-PEMROGRAMAN-PERANGKAT-MOBILE-SESI-6/blob/main/Hasil%20Implementasi/Song%20Detail.jpg" width="45%" />
</p>


---

## 💡 Future Improvements

* Add music player integration (YouTube or Spotify links)
* Offline caching using AsyncStorage
* Search and filter functionality
* Favorite playlist feature

---

## 👩‍💻 Author

**Ranggis**
Developed with ❤️ using React Native and TypeScript.

---

## 📝 License

This project is licensed under the MIT License — feel free to use and modify for learning or development purposes.
