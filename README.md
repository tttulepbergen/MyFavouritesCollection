# 📽️ MyFavoritesCollection

Welcome to **MyFavoritesCollection**, a stylish iOS app to track and showcase your favorite movies! Featuring classic and modern films with their titles, release years, genres, and countries of origin, this app allows you to scroll through a curated list of cinematic treasures.

## 🎬 Features

- **Modern & Classic Films**: Discover an exciting range of movies from timeless classics to recent releases.
- **Genre and Country Information**: Each movie entry includes the genre and country, enriching your browsing experience.
- **Custom Images**: Beautiful, custom images for each movie make this list a visual delight.
- **Dynamic Table View**: Smooth scrolling with details for each film, using Swift and UIKit.

## 📱 Screenshots

<img src="https://github.com/user-attachments/assets/2a200d7a-7d4f-4992-af19-fbd327bd0a0e" width="300" alt="Simulator Screenshot">

## 🚀 Getting Started

### Prerequisites
- Xcode 15.4 or later
- iOS 15.0 or later

### Installation

1. **Clone the Repository**
    ```bash
    git clone https://github.com/yourusername/MyFavoritesCollection.git
    cd MyFavoritesCollection
    ```

2. **Open in Xcode**
    - Open the `.xcodeproj` file in Xcode.
    - Build and run the project on the simulator or your iOS device.

3. **Setup Images**
    - Ensure all custom images (e.g., `basterds.png`, `country.png`, etc.) are added to your Xcode Assets folder for a complete experience.

### Usage

- Open the app, and browse through the collection of movies.
- Each row displays:
  - **Title** of the movie.
  - **Year of Release**.
  - **Genre** to get an idea of the movie’s style.
  - **Country** of origin, adding a cultural touch.

## 🛠️ Code Overview

The project is structured around `UIViewController` and `UITableViewDataSource` to render the list:

- `Movie` struct models each movie’s data.
- `movies` array contains movie instances to populate the table view.
- Custom cells with images, title, genre, and year make the UI intuitive and attractive.

## 💡 Inspiration

MyFavoritesCollection was inspired by a love for cinema and the desire to create an app that blends informative details with a user-friendly experience. This project also serves as a learning ground for exploring `UITableView` functionality in Swift.

## 📚 Technologies Used

- **Swift**: The core programming language.
- **UIKit**: For building the user interface.
- **Xcode**: The development environment.

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the project.
2. Create your feature branch: `git checkout -b feature/AmazingFeature`.
3. Commit your changes: `git commit -m 'Add some AmazingFeature'`.
4. Push to the branch: `git push origin feature/AmazingFeature`.
5. Open a pull request.

