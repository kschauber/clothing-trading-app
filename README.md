# Clothing Trading App

Fullstack project for StackHacks. The repo has two parts:

- `mobile/` is the app (Expo / React Native)
- `backend/` is the server (Node.js + Express)

## Prerequisites

- [Node.js](https://nodejs.org) installed on your computer
- Git
- Expo Go app installed on your phone (only needed for the mobile app)

## Get the code

```bash
git clone https://github.com/kschauber/clothing-trading-app.git
cd clothing-trading-app
```

## Run the backend

From the repo folder, run these one at a time:

```bash
cd backend
npm install
npm start
```

You should see `Server running on http://localhost:3000`.

To test it, open http://localhost:3000/health in your browser. You should see `{"status":"ok"}`.

Press Ctrl+C in the terminal to stop the server.

## Run the mobile app

From the repo folder, run these one at a time:

```bash
cd mobile
npm install
npx expo start
```

This shows a QR code in the terminal. Scan it with your phone camera (iPhone) or the Expo Go app (Android) to open the app. You can also open the web link it prints.

## Contributing

Don't push directly to `main`. Instead:

1. Create a branch: `git checkout -b your-feature-name`
2. Make your changes and commit them
3. Push the branch and open a pull request on GitHub
4. Get one teammate to approve it, then merge