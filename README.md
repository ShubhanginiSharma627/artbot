# Art Generator

Art Generator is a mobile application that allows users to generate art based on text input. Users can input text, which is used to generate an image through an API. They can also choose to overlay the generated image on a picked image from their gallery.

## Features

- Input text to generate art
- Overlay-generated art on a picked image
- View generated art in chat format

## Technologies Used

- Flutter for the front-end
- Dart for the programming language
- HTTP package for making API requests
- Image package for image manipulation
- ImagePicker package for picking images from the gallery

## Setup

To run this application, you need to have Flutter installed on your machine. Follow the Flutter installation guide [here](https://flutter.dev/docs/get-started/install).

1. Clone the repository:

   ```bash
   git clone https://github.com/ShubhanginiSharma627/artbot.git
   ```

2. Navigate to the project directory:

   ```bash
   cd artbot
   ```

3. Run the application:

   ```bash
   flutter run
   ```

## Recording


https://github.com/ShubhanginiSharma627/artbot/assets/63640650/996930b0-58a6-4521-a2e8-fbf23c153189




## API

This application uses the Eden AI API to generate images based on text input. You need to sign up on the Eden AI website to obtain an API key. Update the `token` variable in the `_generate` home_screen.dart` method with your API key.

