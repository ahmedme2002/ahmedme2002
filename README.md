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

<p align="center">
  <a href="#-app-demo">View Demo</a> •
  <a href="#-tech-stack--architecture">Tech Stack</a> •
  <a href="#-ai-implementation-highlights">AI Highlights</a> •
  <a href="#-contact">Contact</a>
</p>

---

## 📱 App Demo
> *Click on any screenshot to view it in full size.*

| **Health Passport** | **Product Scanning** | **AI Ingredient Analysis** | **Safety Alerts** |
|:---:|:---:|:---:|:---:|
| <a href="screenshots/profile_passport.png"><img src="screenshots/profile_passport.png" width="180" alt="User Profile"/></a> | <a href="screenshots/scan_product.png"><img src="screenshots/scan_product.png" width="180" alt="Scanning Product"/></a> | <a href="screenshots/scan_ingredients.png"><img src="screenshots/scan_ingredients.png" width="180" alt="Scanning Ingredients"/></a> | <a href="screenshots/ai_result.png"><img src="screenshots/ai_result.png" width="180" alt="AI Result"/></a> |

---

## 🚀 Overview

**GluGlu** is a collaborative client project designed to help users with severe allergies navigate grocery shopping safely. Unlike standard scanners that rely on simple database lookups, GluGlu integrates **Generative AI** to analyze ingredient labels contextually.

### ✨ Key Features
* **🤖 AI-Powered Analysis:** Uses **OpenAI** to parse complex ingredient lists (e.g., "Casein" = Dairy) and explains *why* a product is unsafe.
* **🌍 Food Passport:** Users create a profile with dietary restrictions (Vegan, Gluten-Free, Peanut Allergy) to get personalized safety results.
* **📷 Dual-Mode Scanning:**
    * **Barcode Scan:** Checks global databases for product metadata.
    * **Visual OCR:** Reads text directly from packaging for items not in the database.
* **⚠️ Smart Alerts:** Instantly identifies hidden allergens and cross-contamination risks.

---

## 🛠️ Tech Stack & Architecture

This project was built with **scalability** and **maintainability** in mind, strictly adhering to Clean Architecture principles.

| Layer | Technology |
| :--- | :--- |
| **Framework** | Flutter (Dart) |
| **State Management** | BLoC (Cubit) |
| **Architecture** | Clean Architecture (Domain, Data, Presentation layers) |
| **AI Integration** | OpenAI API (GPT-4o) with Prompt Engineering |
| **Backend** | Firebase (Auth, Firestore) |
| **Local Storage** | Hive (Offline History) |

---

## 🧠 AI Implementation Highlights

The core innovation of GluGlu is its ability to "understand" ingredients rather than just matching text strings.

### 1. Prompt Engineering
We developed robust system prompts to ensure the AI acts as a **strict dietician**. It is engineered to:
* Identify scientific names for allergens (e.g., "Ovalbumin" → Egg).
* Detect "may contain" warnings for cross-contamination.
* Output strict JSON for UI rendering.

### 2. Structured Data Extraction
The app forces the LLM to return data in a specific format to populate the UI widgets dynamically (as seen in the "Allergens Detected" red chips in the screenshots).

---

## 👥 Team & Contribution

This application was developed as a **collaborative freelance project**.

* **My Role:** Lead Flutter Developer & AI Integrator.
* **Responsibilities:**
    * Architecting the app using Clean Architecture.
    * Implementing the OpenAI integration and camera scanning modules.
    * Managing state with BLoC.
* **Status:** Client project (Production Ready).

---

## 📬 Contact

**Ahmed Abdelkream** - Flutter Developer

<a href="https://linkedin.com/in/ahmed-abdelkream">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin" alt="LinkedIn">
</a>
<a href="mailto:ahmed.abdelkreem.me@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact_Me-red?style=for-the-badge&logo=gmail" alt="Email">
</a>
