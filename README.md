<h1 align="center">GluGlu - AI-Powered Allergy Assistant 🥗</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.24-02569B?logo=flutter" alt="Flutter">
  <img src="https://img.shields.io/badge/AI-OpenAI_GPT_4-412991?logo=openai" alt="OpenAI">
  <img src="https://img.shields.io/badge/Backend-Firebase-FFCA28?logo=firebase" alt="Firebase">
  <img src="https://img.shields.io/badge/Architecture-Clean_Arch-green" alt="Clean Architecture">
</p>

<p align="center">
  <strong>A production-grade health application that uses AI to analyze food and cosmetic ingredients for allergens in real-time.</strong>
</p>

---

## 📱 App Demo

| **Personalized Health Passport** | **Smart Product Scanning** | **AI Ingredient Analysis** | **Instant Safety Alerts** |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/profile_passport.png" width="200" alt="User Profile and Food Passport showing allergies like Gluten and Peanuts"/> | <img src="screenshots/scan_product.png" width="200" alt="Scanning a shampoo bottle with barcode and camera"/> | <img src="screenshots/scan_ingredients.png" width="200" alt="Scanning nutrition facts on a can"/> | <img src="screenshots/ai_result.png" width="200" alt="AI Analysis showing allergens detected in Orange Juice"/> |

---

## 🚀 Overview

**GluGlu** is a freelance project developed to help users with severe allergies navigate grocery shopping safely. Unlike standard scanners that rely on simple database lookups, GluGlu integrates **Generative AI** to analyze ingredient labels contextually.

The app allows users to create a "Food Passport" with their specific dietary restrictions (Gluten, Peanuts, Vegan, etc.) and instantly scans products to detect hidden risks.

### ✨ Key Features

* **🤖 AI-Powered Analysis:** Leverages the **OpenAI API** to parse complex ingredient lists and generate natural language summaries of *why* a product is safe or unsafe.
* **🌍 Food Passport:** A personalized user profile system that stores allergy data and cuisine preferences to customize scan results.
* **📷 Dual-Mode Scanning:**
    * **Barcode Scan:** Fetches product metadata from global databases.
    * **OCR / Visual Scan:** Recognizes text on bottles and cans (e.g., Shampoo, Canned Goods) for products not in the database.
* **⚠️ Real-Time Alerts:** Instantly flags detected allergens (e.g., "Gluten," "Egg," "Fish") with clear visual warnings.

---

## 🛠️ Tech Stack & Architecture

This project follows **Clean Architecture** principles to ensure scalability and testability.

* **Framework:** Flutter (Dart)
* **State Management:** BLoC (Business Logic Component)
* **AI Integration:** OpenAI API (Prompt Engineering for strict JSON output & safety analysis)
* **Backend:** Firebase (Authentication, Cloud Firestore)
* **Data Sources:** Open Food Facts API + Custom AI Parsing
* **Local Storage:** Hive (for offline search history)

---

## 🧠 AI Implementation Highlights

The core value of GluGlu is its ability to "understand" ingredients rather than just matching text.

* **Prompt Engineering:** Developed robust system prompts to ensure the AI acts as a strict dietician, identifying cross-contamination risks and hidden names for allergens (e.g., identifying "Casein" as Dairy).
* **Structured Data Extraction:** The app forces the LLM to return data in structured JSON format to populate the UI widgets dynamically (as seen in the "Allergens Detected" chips).

---

## 👥 Team & Contribution

This application was developed as a **collaborative freelance project**.

* **My Role:** Lead Flutter Developer & AI Integrator. Responsible for the Clean Architecture setup, OpenAI API integration, and the scanning module.
* **Status:** Client project (Production Ready).

---

## 📬 Contact

**Ahmed Abdelkream** - Flutter Developer
* [LinkedIn](https://linkedin.com/in/ahmed-abdelkream)
* [Email](mailto:<h1 align="center">GluGlu - AI-Powered Allergy Assistant 🥗</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Flutter-3.24-02569B?logo=flutter" alt="Flutter">
  <img src="https://img.shields.io/badge/AI-OpenAI_GPT_4-412991?logo=openai" alt="OpenAI">
  <img src="https://img.shields.io/badge/Backend-Firebase-FFCA28?logo=firebase" alt="Firebase">
  <img src="https://img.shields.io/badge/Architecture-Clean_Arch-green" alt="Clean Architecture">
</p>

<p align="center">
  <strong>A production-grade health application that uses AI to analyze food and cosmetic ingredients for allergens in real-time.</strong>
</p>

---

## 📱 App Demo

| **Personalized Health Passport** | **Smart Product Scanning** | **AI Ingredient Analysis** | **Instant Safety Alerts** |
|:---:|:---:|:---:|:---:|
| <img src="screenshots/profile_passport.png" width="200" alt="User Profile and Food Passport showing allergies like Gluten and Peanuts"/> | <img src="screenshots/scan_product.png" width="200" alt="Scanning a shampoo bottle with barcode and camera"/> | <img src="screenshots/scan_ingredients.png" width="200" alt="Scanning nutrition facts on a can"/> | <img src="screenshots/ai_result.png" width="200" alt="AI Analysis showing allergens detected in Orange Juice"/> |

---

## 🚀 Overview

**GluGlu** is a freelance project developed to help users with severe allergies navigate grocery shopping safely. Unlike standard scanners that rely on simple database lookups, GluGlu integrates **Generative AI** to analyze ingredient labels contextually.

The app allows users to create a "Food Passport" with their specific dietary restrictions (Gluten, Peanuts, Vegan, etc.) and instantly scans products to detect hidden risks.

### ✨ Key Features

* **🤖 AI-Powered Analysis:** Leverages the **OpenAI API** to parse complex ingredient lists and generate natural language summaries of *why* a product is safe or unsafe.
* **🌍 Food Passport:** A personalized user profile system that stores allergy data and cuisine preferences to customize scan results.
* **📷 Dual-Mode Scanning:**
    * **Barcode Scan:** Fetches product metadata from global databases.
    * **OCR / Visual Scan:** Recognizes text on bottles and cans (e.g., Shampoo, Canned Goods) for products not in the database.
* **⚠️ Real-Time Alerts:** Instantly flags detected allergens (e.g., "Gluten," "Egg," "Fish") with clear visual warnings.

---

## 🛠️ Tech Stack & Architecture

This project follows **Clean Architecture** principles to ensure scalability and testability.

* **Framework:** Flutter (Dart)
* **State Management:** BLoC (Business Logic Component)
* **AI Integration:** OpenAI API (Prompt Engineering for strict JSON output & safety analysis)
* **Backend:** Firebase (Authentication, Cloud Firestore)
* **Data Sources:** Open Food Facts API + Custom AI Parsing
* **Local Storage:** Hive (for offline search history)

---

## 🧠 AI Implementation Highlights

The core value of GluGlu is its ability to "understand" ingredients rather than just matching text.

* **Prompt Engineering:** Developed robust system prompts to ensure the AI acts as a strict dietician, identifying cross-contamination risks and hidden names for allergens (e.g., identifying "Casein" as Dairy).
* **Structured Data Extraction:** The app forces the LLM to return data in structured JSON format to populate the UI widgets dynamically (as seen in the "Allergens Detected" chips).

---

## 👥 Team & Contribution

This application was developed as a **collaborative freelance project**.

* **My Role:** Lead Flutter Developer & AI Integrator. Responsible for the Clean Architecture setup, OpenAI API integration, and the scanning module.
* **Status:** Client project (Production Ready).

---

## 📬 Contact

**Ahmed Abdelkream** - Flutter Developer
* [LinkedIn](https://linkedin.com/in/ahmed-abdelkream)
* [Email](mailto:ahmed.abdelkreem.me@gmail.com))
