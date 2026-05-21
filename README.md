# Rytham - Flutter Music Player

A modern, feature-rich local music player for Android built with Flutter. Rytham provides an intuitive interface for browsing, playing, and managing your music library with advanced playback controls and customization options.

## Features

- 🎵 **Local Music Library**: Browse and play music from your device storage
- 🔍 **Search & Filter**: Quickly find songs by title or artist
- ❤️ **Favorites**: Mark your favorite songs for quick access
- 🎚️ **Playback Controls**: Play, pause, skip, shuffle, and repeat modes
- 🌙 **Dark/Light Mode**: Toggle between dark and light themes
- 📱 **Material Design 3**: Modern, responsive UI with Material Design 3 guidelines
- ⚡ **Smooth Performance**: Optimized for fast loading and smooth playback

## Architecture

- **State Management**: Provider pattern with ChangeNotifier
- **Audio Engine**: just_audio for playback control
- **Library Access**: on_audio_query for device music library access
- **Persistence**: SharedPreferences for user preferences and favorites
- **UI Framework**: Flutter with Material Design 3

## Dependencies

- flutter (SDK: >=3.0.0 <4.0.0)
- provider: ^6.1.2
- just_audio: ^0.9.36
- on_audio_query: ^2.9.0
- mini_music_visualizer: ^0.0.1
- google_fonts: ^6.2.1
- shared_preferences: ^2.2.3
- flutter_lints: ^3.0.0

## Getting Started

### Prerequisites

- Flutter SDK (>=3.0.0)
- Android SDK (for Android development)
- Connected Android device or emulator

### Installation

1. Clone the repository:
```bash
git clone https://github.com/SatheeshKumar2412/rytham.git
cd rytham
```

2. Install dependencies:
```bash
flutter pub get
```

3. Run the app:
```bash
flutter run
```

### Building for Release

Create a release APK:
```bash
flutter build apk --release
```

## Project Structure

```
lib/
├── main.dart           # Main app entry point and all app code
pubspec.yaml           # Project configuration and dependencies
```

## Usage

### Playing Music
1. Open the app and browse your music library
2. Tap on any song to play it
3. Use the player controls to manage playback

### Managing Favorites
- Tap the heart icon next to any song to add/remove from favorites
- View all favorite songs in your library

### Switching Themes
- Go to Settings (gear icon)
- Toggle "Dark Mode" to switch between light and dark themes

## Screens

- **Home Screen**: Main library view with search and song list
- **Player Screen**: Full-featured player with playback controls
- **Settings Screen**: Theme and app preferences

## Permissions Required

- `READ_EXTERNAL_STORAGE`: To access device music files
- `READ_MEDIA_AUDIO`: Android 13+ audio file access

## Known Limitations

- Currently Android-only
- Requires device music files stored in standard music folders
- Basic shuffle and repeat modes (advanced queue management planned)

## Future Enhancements

- iOS support
- Equalizer with audio enhancement presets
- Playlist management and export
- Download support for streaming sources
- NowPlaying widget
- Notification controls
- Scrobbling integration

## Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests for any improvements.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Author

Created with ❤️ for music lovers

## Support

For issues, feature requests, or questions, please open an issue on GitHub.
