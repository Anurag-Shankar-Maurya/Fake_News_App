# FakeHai: An Android Application for Fake News Detection

FakeHai is an Android application designed to help users identify potentially fake news.  It leverages the power of Google's Gemini API to analyze news articles and determine their veracity.  Users input the title, text, and subject of a news item, and FakeHai uses this information to assess the likelihood of it being genuine or fake.

---

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Screenshots](#screenshots)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [API Key](#api-key)
- [Contributing](#contributing)
- [Contact](#contact)

---
## Introduction

In today's world of information overload, distinguishing between real and fake news can be challenging. FakeHai aims to simplify this process by providing a user-friendly interface to quickly check the credibility of news articles.  By utilizing the advanced capabilities of the Gemini API, FakeHai analyzes the provided information and returns a result indicating whether the news is likely to be fake or real.

---

## Features

- **Easy-to-use Interface:**  A simple and intuitive interface allows users to easily input news details.
- **Gemini API Integration:** Leverages the Gemini API for accurate and efficient fake news detection.
- **Real-time Results:** Provides quick feedback on the likelihood of the news being fake.
- **Clear Visual Indicators:** Uses clear visual cues (icons) to represent the result (fake or real).
- **Subject Categorization:** Allows users to specify the subject of the news (e.g., political, sports, etc.) for more accurate analysis.
- **Loading Indicator:**  Displays a progress bar while the news is being analyzed.

---

## Screenshots
<div style="display: flex; flex-wrap: nowrap; gap: 10px; justify-content: space-evenly;">

<img src="https://github.com/user-attachments/assets/a23d9427-108f-42b5-a117-725bbd195caf" alt="Splash Screen" width="150">
<img src="https://github.com/user-attachments/assets/208b9774-44f8-4367-b1b1-49cbeb89d301" alt="Main Screen 1" width="150">
<img src="https://github.com/user-attachments/assets/8222b7a6-9e2e-4f6f-ab0d-247fff7b230e" alt="Main Screen 2" width="150">
<img src="https://github.com/user-attachments/assets/519c8da1-724b-4d38-bd94-552953c8b7ca" alt="Angry Behavior" width="150">
<img src="https://github.com/user-attachments/assets/f07aa352-60a8-4f93-89af-ef8489ec3253" alt="Thor" width="150">
</div>

---

## Technologies Used

- **Android SDK:**  For building the Android application.
- **Kotlin:**  The primary programming language used.
- **Android Studio:**  The IDE used for development.
- **Google Gemini API:**  For fake news detection.
- **ConstraintLayout:** For layout design.

---

## Installation

1. Clone the repository: `git clone https://github.com/Anurag-Shankar-Maurya/FakeHai.git`
2. Open the project in Android Studio.
3. Add your Gemini API key (see [API Key](#api-key) section below).
4. Build and run the application on an Android emulator or device.

---

## Usage

1. Enter the title of the news article in the "Enter News Title" field.
2. Enter the content/text of the news article in the "Enter News Text" field.
3. Select the subject category of the news (e.g., political, sports, etc.) in the "Enter Subject" field.
4. Click the "Check News" button.
5. The app will display a loading indicator while processing.
6. The result will be displayed with a corresponding icon (a checkmark for real news, and potentially an "X" or other indicator for fake news).

---

## API Key

This application requires a Google Gemini API key.  You can obtain one by following the instructions on the Google AI website.  **Replace `YOUR_API_KEY` in the `BuildConfig.kt` file with your actual API key.**  Do not commit your API key to the repository.

```kotlin
// In BuildConfig.kt
buildConfigField("String", "apiKey", "YOUR_API_KEY") // Replace with your actual key
```
---

## Contributing

Contributions are welcome!  Please feel free to submit pull requests or open issues to suggest improvements or report bugs.

---

## Contact

Anurag Shankar Maurya - [anuragshankarmaurya@gmail.com](anuragshankarmaurya@gmail.com) - [LinkedIn Profile](https://www.linkedin.com/in/anurag-shankar-maurya/)
