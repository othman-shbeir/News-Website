# 📰 News Website

A modern **Angular-based news aggregation platform** that fetches and displays the latest headlines, business, and technology news using the **NewsAPI**. This project offers users a simple and responsive interface to stay up-to-date with the world’s top stories.

---

## 🚀 Features

* **Top Headlines:** Displays the latest top news from trusted sources.
* **Technology News:** Get the newest trends and updates in tech.
* **Business News:** Follow the most recent stories in the business world.
* **Dynamic Routing:** Seamless navigation between news categories using Angular Router.
* **Loading Bar Integration:** Displays progress indicators using `@ngx-loading-bar`.
* **Responsive Design:** Built with **Bootstrap 5** for cross-device compatibility.

---

## 🧩 Tech Stack

* **Framework:** Angular 15
* **Language:** TypeScript
* **Styling:** Bootstrap 5, CSS3
* **API:** [NewsAPI.org](https://newsapi.org)
* **HTTP Client:** Angular HttpClient

---

## 📁 Project Structure

```
othman-shbeir-news-website/
├── src/
│   ├── app/
│   │   ├── topheading/            # Displays top news headlines
│   │   ├── tech-news/             # Technology news section
│   │   ├── business-news/         # Business news section
│   │   └── services/              # News API integration service
│   ├── assets/                    # Static assets
│   ├── styles.css                 # Global styles
│   ├── index.html                 # App entry point
│   └── main.ts                    # Main module bootstrap
├── angular.json                   # Angular configuration
├── package.json                   # Dependencies and scripts
└── tsconfig.json                  # TypeScript configuration
```

---

## 🧠 Architecture Overview

This Angular project follows a **modular architecture**, where each news category (Top, Tech, Business) is encapsulated as a standalone component. The `NewsApiServicesService` centralizes API calls and data management, making it reusable and maintainable.

### Components Overview

* **`TopheadingComponent`** – Fetches and displays top global headlines.
* **`TechNewsComponent`** – Displays technology-related news articles.
* **`BusinessNewsComponent`** – Focuses on business and financial news.

### Service Layer

* **`NewsApiServicesService`** – Handles all API requests and exposes observables to components for async data updates.

---

## ⚙️ Installation & Setup

### Prerequisites

* Node.js >= 16
* Angular CLI >= 15

### Steps

```bash
# Clone the repository
git clone https://github.com/othman-shbeir/news-website.git
cd news-website

# Install dependencies
npm install

# Start the development server
ng serve
```

Visit **`http://localhost:4200/`** in your browser.

---

## 🔑 API Configuration

This project uses [NewsAPI](https://newsapi.org). You’ll need an API key to fetch live data.

1. Create a free account on [NewsAPI.org](https://newsapi.org/register).
2. Replace the existing API key in `news-api-services.service.ts` with your own:

```typescript
newsApiUrl = 'https://newsapi.org/v2/top-headlines?sources=bbc-news&apiKey=YOUR_API_KEY';
```

---

## 🧪 Running Tests

Run unit tests using Karma:

```bash
ng test
```

---

## 🏗️ Build for Production

To build the project for production:

```bash
ng build --configuration production
```

The output will be located in the `dist/` directory.

---

## 👨‍💻 Author

**Eng.Othman Shbeir**
- 📧 [ahmedshbeir30@gmail.com](mailto:uthmanshbeir@gmail.com)
- 🌐 [Portfolio](https://othman-shbeir.github.io)
- 🔗 [LinkedIn](https://www.linkedin.com/in/othman-shbeir)

---

### ⭐ Acknowledgments

* [Angular Team](https://angular.io)
* [NewsAPI](https://newsapi.org)
* [Bootstrap](https://getbootstrap.com)

> *Developed with passion and precision by Othman Shbeir* 💻
