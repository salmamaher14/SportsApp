# ⚽ SportSpire

An iOS app that gives sports fans detailed information about their favorite sports: leagues, recent results, team details, and upcoming events, all in one place.

![Platform](https://img.shields.io/badge/platform-iOS-blue)
![Language](https://img.shields.io/badge/language-Swift-orange)
![Architecture](https://img.shields.io/badge/architecture-MVVM-green)

## 🎬 Demo

[▶️ Watch the demo video](https://drive.google.com/file/d/1krmzkStg2FEpimNaRaut1MFGgKw3vVq3/view?usp=sharing)

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

<table align="center">
  <tr>
    <td align="center"><b>Home</b></td>
    <td align="center"><b>Leagues</b></td>
    <td align="center"><b>League Details</b></td>
    <td align="center"><b>Teams</b></td>
    <td align="center"><b>Team Details</b></td>
    <td align="center"><b>Favorites</b></td>
    <td align="center"><b>Favorite Details</b></td>

  </tr>
  <tr>
    <td><img width="150" src="https://github.com/user-attachments/assets/fc68372e-1c00-4f9f-8517-8bcd47dbe7dd" /></td>
    <td><img width="150" src="https://github.com/user-attachments/assets/733cb552-ea5e-48ac-a414-63eccfd5ab8b" /></td>
    <td><img width="150" src="https://github.com/user-attachments/assets/77285ab4-21c8-4f8b-bbc7-b4107b8f9dfb" /></td>
    <td><img width="150" src="https://github.com/user-attachments/assets/fab7dfdf-5b8e-4cfb-a2f3-1b1c82270950" /></td>
    <td><img width="150" src="https://github.com/user-attachments/assets/110375b2-d436-4da7-8fb3-0943d56cc9dd" /></td>
    <td><img width="150" src="https://github.com/user-attachments/assets/45f883bb-e589-4bd6-8480-c495fcf25034" /></td>
    <td><img width="150" src="https://github.com/user-attachments/assets/a0bd5076-312f-443f-a09e-201810fe7a39" /></td

  </tr>
</table>

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

## 👥 Contributors

| Name | GitHub |
|------|--------|
| **Naden Mohamed** | [naden43](https://github.com/naden43) |
| **Salma Maher** | [salmamaher14](https://github.com/salmamaher14) |
