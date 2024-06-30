# RN-APP-STARTER (React Native CLI App)

A comprehensive **React Native CLI** template providing a robust folder structure for building scalable mobile applications. This template includes best practices, essential libraries, and a modular architecture to kickstart your React Native projects with ease.

## Folder Structure

- **src/**: Main source directory
  - **assets/**: Contains fonts and images
    - **fonts/**: Add your custom fonts here
    - **images/**: Add your custom images here
  - **route/**: Contains screens and their components
    - **screenName/**: Screen structure
      - `index.js`: Entry point
      - `styles.ts`: Styles for the screen
      - `helper.ts`: Helper functions
      - `screenName.tsx`: Screen component
      - `screenName.test.tsx`: Tests for the screen
      - `useAnimated.ts` (Optional): Animation hooks
      - `components/` (Optional): Screen-specific components
  - **navigation/**: Navigation setup
    - `NavigationContainer`: Main navigation container
    - `Route`: Route definitions
    - `NavigationService`: Navigation services
    - `linking`: Linking configuration
  - **networking/**: Networking utilities
    - `apiclient`: API client setup
    - `requestInterceptor`: Request interceptor (Axios)
    - `responseInterceptor`: Response interceptor (Axios)
    - `urls`: API URLs
    - `UserApi`: User-related API calls
  - **components/**: Reusable components
    - `Button/`: Example component structure
      - `index.ts`: Entry point
      - `Button.tsx`: Button component
      - `styles.ts`: Styles for the button
      - `helper.ts`: Helper functions
      - `useAnimated.ts` (Optional): Animation hooks
  - **hooks/**: Custom hooks
    - `useBackHandler.ts`: Back handler hook
    - `useKeyboard.ts`: Keyboard handling hook
    - `useUploadImage.ts`: Image upload hook
    - `useCamera.ts`: Camera hook
  - **types/**: Type definitions
    - `UserInterface`: User interface types
    - `MediaInterface`: Media interface types
    - `AppConfigInterface`: App configuration types
  - **redux/**: Redux setup
    - `store.ts`: Redux store
    - `slices/`: Redux slices
      - `UserSlice`: User slice
      - `IntermittentSlice`: Intermittent slice
      - `ToastSlice`: Toast slice
  - **utils/**: Utility functions
    - `Analytics.ts`: Analytics utilities
    - `CommonUtils.ts`: Common utility functions
    - `Logger.ts`: Logger utility
    - `ErrorManager.ts`: Error management
    - `DateTimeUtils.ts`: Date/time utilities
    - `EncryptedStore.ts`: Encrypted storage
    - `string.ts`: String utilities
    - `constants.ts`: Constant values
    - `enums.ts`: Enumerations
  - **Module_Name/**: Modules for multi-module apps
    - `routes/`
    - `components/`
    - `hooks/`

## Installation

1. **Clone the repository**:

   ```bash
   git clone <repository-url>
   cd <repository-name>
   ```

2. **Install dependencies:**:

   ```bash
   yarn install
   ```

3. **Change app name and other configurations:**

   - Modify app.json for app-specific settings like name, display name, and icons.
   - Update any necessary configurations in src/config/ if applicable.

4. **Run the app:**
   ```bash
   yarn android   # For Android
   yarn ios       # For iOS
   ```

## **Customization**

- App Name: Change in app.json.
- Assets: Place fonts in src/assets/fonts/ and images in src/assets/images/.
- API URLs: Modify in src/networking/urls/.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## 🌐 Connect with me

- [Linkedin](https://www.linkedin.com/in/henil-mehta/)
- [Instgram](https://www.instagram.com/henil17.08/?hl=en)
- [Twitter](https://x.com/Mehta11Henil)
<p align="center">Made with ❤️ by <a href='https://dizilus.com/home'>Dizilus</a></p>
