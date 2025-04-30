# Form Application

## Overview

This is a React Native application built with Expo, likely focused on creating and managing forms, potentially including a checkout process. It utilizes Expo Router for navigation and includes various custom UI components.

## Project Structure

The application follows the standard Expo Router file-based routing structure within the `src/app` directory:

```
src/app/
├── _layout.tsx         # Main layout for the app
├── index.tsx           # Home screen or initial screen
└── checkout/           # Directory for checkout-related screens
    ├── _layout.tsx     # Layout specific to the checkout flow
    ├── index.tsx       # Initial screen of the checkout flow
    ├── personal.tsx    # Screen for personal information
    ├── payment.tsx     # Screen for payment details
    └── confirm.tsx     # Screen for order confirmation
```

## Components

The application uses several custom components located in `src/components`:

- `CheckoutFormStepIndicator.tsx`: Likely displays the current step in the checkout process.
- `CustomButton.tsx`: A reusable button component.
- `CustomCheckbox.tsx`: A reusable checkbox component.
- `CustomDateTimePicker.tsx`: A component for selecting dates and times.
- `CustomPicker.tsx`: A reusable picker/dropdown component.
- `CustomSwitch.tsx`: A reusable switch component.
- `CustomTextInput.tsx`: A reusable text input component.
- `KeyboardAwareScrollView.tsx`: A ScrollView that adjusts to the keyboard's presence.

## Getting Started

### Prerequisites

- Node.js and npm/yarn/bun installed
- Expo Go app on your mobile device or an emulator/simulator setup

### Installation

1.  **Clone the repository:**
    ```bash
    git clone <your-repository-url>
    cd Form
    ```
2.  **Install dependencies:**
    ```bash
    bun install
    ```

### Running the App

1.  **Start the development server:**
    ```bash
    npx expo start
    ```
2.  Follow the instructions in the terminal to open the app on your device or simulator.
