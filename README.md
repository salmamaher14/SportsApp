# ⚽ SportSpire

An iOS app that gives sports fans detailed information about their favorite sports: leagues, recent results, team details, and upcoming events, all in one place.

![Platform](https://img.shields.io/badge/platform-iOS-blue)
![Language](https://img.shields.io/badge/language-Swift-orange)
![Architecture](https://img.shields.io/badge/architecture-MVVM-green)

## 🎬 Demo

https://github.com/<your-username>/SportSpire/assets/<video-id>

> Tip: to embed the video, drag and drop the file into the README editor on GitHub (it will generate the link for you). You can also link a YouTube video instead:
> `[![Watch the demo](screenshots/home.png)](https://youtu.be/<video-id>)`

## 📱 Features

- Browse sports leagues
- View recent match results
- Explore league and team details
- Check upcoming events
- Save favorite leagues and access them offline (Core Data)
- Dedicated Favorites screen to manage your saved leagues
- Smooth animations with Lottie
- Fast, cached image loading with Kingfisher

## 📸 Screenshots

<p align="center">
  <img src="screenshots/home.png" width="200"/>
  <img src="screenshots/leagues.png" width="200"/>
  <img src="screenshots/league-details.png" width="200"/>
  <img src="screenshots/favorites.png" width="200"/>
</p>

| Home | Leagues | League Details | Favorites |
|:----:|:-------:|:--------------:|:---------:|

## 🛠 Tech Stack

| Category | Technology |
|----------|-----------|
| Language | Swift |
| UI | UIKit, Storyboards, Nib files |
| Architecture | MVVM |
| Networking | Alamofire, RESTful API |
| Image Loading | Kingfisher |
| Local Storage | Core Data |
| Animations | Lottie |
| Testing | XCTest, Unit Testing |
| Version Control | Git, GitHub |

## 🏗 Architecture

The project follows the **MVVM** pattern:

- **Model**: data structures and Core Data entities
- **View**: UIKit view controllers, Storyboards, and Nib files
- **ViewModel**: presentation logic and data binding between the network/local layers and the views

```
SportSpire/
├── Models/
├── Views/
├── ViewModels/
├── Network/
├── CoreData/
├── Resources/
└── Tests/
```

## 🚀 Getting Started

### Prerequisites

- Xcode 14 or later
- iOS 14.0 or later
- CocoaPods or Swift Package Manager (depending on your setup)

### Installation

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/SportSpire.git
   ```
2. Navigate to the project folder
   ```bash
   cd SportSpire
   ```
3. Install dependencies (if using CocoaPods)
   ```bash
   pod install
   ```
4. Open the project in Xcode
   ```bash
   open SportSpire.xcworkspace
   ```
5. Build and run on a simulator or a real device


## 👥 Contributors

| Name | GitHub |
|------|--------|
| **Naden Mohamed** | [naden43](https://github.com/naden43) |
| **Salma Maher** | [salmamaher14](https://github.com/your-username) |










