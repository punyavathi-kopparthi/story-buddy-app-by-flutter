# Story Buddy

A child-friendly Flutter application that narrates a short story using Text-to-Speech (TTS) and then presents an interactive quiz based on the story.

## Features

* Flutter-based UI
* Text-to-Speech narration
* Interactive multiple-choice quiz
* Correct and incorrect answer feedback
* Responsive design

## Architecture

The application uses a simple StatefulWidget architecture.

### Components

* StoryBuddyApp: Root application widget
* StoryScreen: Main screen containing story narration and quiz
* FlutterTts: Handles audio narration
* Quiz Logic: Displays questions after narration completes

## State Management

The app currently manages state using Flutter's built-in StatefulWidget and setState().

## Dependencies

* flutter_tts
* confetti

## How to Run

1. Clone the repository
2. Run:

flutter pub get

3. Start the application:

flutter run

## Future Improvements

* JSON-based quiz loading
* Confetti celebration animation
* Better error handling
* Multiple stories support
* Progress tracking

## Author

Developed as part of the Story Buddy Flutter Assessment.
