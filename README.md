# SmartBazaar: A Digital Agri-Marketplace for Empowering Small Farmers

SmartBazaar is a localized, intelligent, and transparent digital marketplace designed to address agricultural inefficiencies in Pakistan. By connecting small-scale farmers directly with wholesalers and retailers, the platform eliminates middleman exploitation and provides farmers with the tools needed to maximize their income and financial stability.

---

## ## Key Features

### 🌾 For Farmers

- **Direct Marketplace:** List produce with photos, quantities, and units to connect directly with buyers.

- **Fair Price Suggestion:** Receive recommended pricing based on real-time regional averages, supply (active listings), demand (orders), and location.

- **Daily AI Farming Report:** Get personalized daily insights including weather, soil conditions, irrigation/fertilizer schedules, and market trends.

- **Order Management:** Track sales history and update delivery statuses in real-time.

### 🛒 For Buyers

- **Smart Matching:** Find relevant produce using text embedding-based searches that filter by location, price, and crop name.

- **Efficient Purchasing:** Save listings, place orders, view purchase history, and easily reorder from farmers.

### 🤖 Intelligent Assistance & Accessibility

- **AgroGuru Assistant:** An AI chatbot providing advice on pest management, seasonal planning, and risk alerts in Urdu or English.

- **Multilingual Support:** The interface is dynamically translated into Urdu, Punjabi, Sindhi, and Pashto to ensure inclusivity for rural users.

- **Real-time Communication:** A seamless farmer-buyer chat system powered by Firebase Cloud Messaging (FCM).

---

## ## Technical Architecture

SmartBazaar leverages a fully serverless architecture built on **Firebase** and **Google AI** services for maximum scalability and efficiency.

| Component             | Usage                                                                                    |
| --------------------- | ---------------------------------------------------------------------------------------- |
| **Google Gemini API** | Powers real-time translation, crop image classification, farming reports, and AI advice. |

|
| **Firestore** | Acts as the primary NoSQL database for listings, user profiles, and transaction metadata.

|
| **Firebase Auth** | Manages secure, role-based onboarding (Farmer/Buyer) via phone or email.

|
| **Firebase Cloud Messaging** | Handles instant notifications for new listings, buyer matches, and order updates.

|
| **Genkit** | Used to implement AI functionalities with the Gemini API.

|
| **Firebase App Hosting** | Provides global scalability and hosting for the platform.

|
| **GitHub Actions** | Fetches market data hourly to update price embeddings in Firestore.

|

---

## ## Workflow & Business Model

1.  **Onboarding:** Users register and provide profile data (CNIC, phone, location) stored securely in Firestore.

2.  **Listing & Sale:** Farmers list goods; buyers are matched via AI embeddings.

3.  **Communication:** Buyers and farmers negotiate and coordinate via the integrated chat system.

4.  **Revenue:** The platform sustains operations through a **2% commission** on every successful sale.

---

## ## Impact

In a region where over 60% of farmers lack access to transparent markets, SmartBazaar provides a vital link to the digital economy. Its intuitive design is specifically tailored for new smartphone users in rural communities.

## Demo Video

[Watch the Demo](https://drive.google.com/file/d/1eVRNjFGbA8n3--TuDJqzwBHupej6apAh/view?usp=drive_link)
