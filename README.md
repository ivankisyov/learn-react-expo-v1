# Welcome to your Expo app 👋

This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).

## Get started

1. Install dependencies

   ```bash
   npm install
   ```

2. Start the app

   ```bash
    npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

## Get a fresh project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

## Learn more

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

## Join the community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.

---

# Custom notes start here

## Tutorial app

### Commands

- start the app: `npx expo start`

### Libs and additional packages

- expo/vector-icons
- expo-image-picker

### VS code Plugins

- dsznajder: ES7+ React/Redux/React-Native snippets

### TIL

- Day 1: https://reactnative.directory/
- Day 2: useRef and more on hooks: https://www.youtube.com/watch?v=t2ypzz6gJm0&ab_channel=WebDevSimplified
- Day 3: Junior React Developers mistakes: https://www.youtube.com/watch?v=-yIsQPp31L0&ab_channel=ByteGrad
- Day 4: React Best Practices: https://www.youtube.com/watch?v=5r25Y9Vg2P4&ab_channel=ByteGrad
  - avoid props drilling by either:
    - using children approach
    - using state management approach:
      - context api
      - zustand
      - some other redux oriented pattern
- use single state instead of multiple states
  - example:
    - handling api call
      - declare multiple state variables:
        - isLoading
        - hasError
        - ...
      - instead use single status state variable, it will be an union
        - the status can be:
          - 'idle'
          - 'error'
          - 'success'
          - 'loading'

### Running the app on android and iOS emulators

- https://www.youtube.com/watch?v=xKGESzemfdw&t=122s&ab_channel=Codevolution
- https://www.youtube.com/watch?v=DloY4tyzKDA&ab_channel=Codevolution
