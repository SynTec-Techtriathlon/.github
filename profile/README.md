Application system contains three main repositories : a Flutter-based mobile application (front-end), an ASP.NET Core API (back-end), a ViteJs (front-end) admin panel.

## Prerequisites

Before you begin, ensure you have the following software installed:

- [Flutter](https://flutter.dev/docs/get-started/install)
- [.NET SDK](https://dotnet.microsoft.com/download)
- [Node js](https://nodejs.org/en/download/package-manager)

## Setup Instructions
All of below three repositories are needed to simulate the full functionality of the system

### User Mobile App (flutter)

1. Navigate to the `frontend` directory by running `cd frontend`.
2. Install Flutter dependencies with `flutter pub get`.
3. Update the API endpoint URL in the Flutter project, typically found in a configuration file like `lib/config.dart`.

### Backend API (ASP.NET Core)

1. Clone the `backendRepo` repository
2. Restore NuGet packages using `dotnet restore`/ Automatically installed if Visual Studio is used
3. Build & Run

### Admin front end (ViteJs)

1. Clone the `Admin-WebFrontEnd` repository
2. Install Node modules with `npm install`
3. Run the dev server by `npm run dev`



