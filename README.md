# 🚀 Netflix UI Clone in Flutter using BloC
The Project uses BloC package to manage the state and GoRouter for navigation. It use the awesome [TMDB](https://www.themoviedb.org/) [API](https://www.themoviedb.org/documentation/api) to fetch the needed tv shows and movie data.

# Running
1. Get Packages
```dart
flutter pub get
```
2. Get an API key from [TMDB](https://www.themoviedb.org/documentation/api) and replace it in `lib/api/api.dart`
```dart
final apiKey = 'INSERT_YOUR_API_KEY_HERE';
```
3. Run App
```dart
flutter run --release
```
