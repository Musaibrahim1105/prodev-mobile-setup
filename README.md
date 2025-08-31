# prodev-mobile-setup

# Mobile Development Setup with Expo Go

## Objective
Mobile development requires more resources than web development. To make the process smooth, we are using the **Expo Framework** for React Native, and testing apps with **Expo Go** on physical devices.

## Prerequisites
- Node.js LTS installed (`node -v` → vXX.XX.X)
- npm installed (`npm -v` → vX.XX.X)
- VS Code installed
- macOS (my development environment)
- A physical device (iPhone/Android) with Expo Go installed

## Steps Taken
1. Installed Expo Go:
   - iOS → via App Store  
   - Android → via Google Play Store
2. Created an Expo account and logged in.
3. Verified installation by running:
   ```bash
   npx expo start
## Observations from thereset-project command

Do you want to move existing files to /app-example instead of deleting them? (Y/n): y
📁 /app-example directory created.
➡️ /app moved to /app-example/app.
➡️ /components moved to /app-example/components.
➡️ /hooks moved to /app-example/hooks.
➡️ /constants moved to /app-example/constants.
➡️ /scripts moved to /app-example/scripts.

📁 New /app directory created.
📄 app/index.tsx created.
📄 app/_layout.tsx created.

✅ Project reset complete. Next steps:
1. Run `npx expo start` to start a development server.
2. Edit app/index.tsx to edit the main screen.
3. Delete the /app-example directory when you're done referencing it.


## Observations from `npm run reset-project`
- Running `reset-project` moves existing files into `/app-example/` if you confirm with `y`.
- This means the original `app/`, `components/`, `hooks/`, etc. are preserved but relocated into `app-example/`.
- If you choose `n`, those files will be deleted permanently.
- Useful for resetting to a clean template without losing everything.
