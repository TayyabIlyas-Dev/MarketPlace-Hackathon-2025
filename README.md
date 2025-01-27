# Hackathon Market Place (GIAIC)

## E-Commerce Platform: Premii Woods 🛋️

Welcome to the official repository for **Premii Woods**—an e-commerce platform dedicated to premium furniture tailored for designers, gamers, and creators. This repository showcases API integration, data migration to Sanity CMS, and dynamic content rendering with Next.js.

---

## Features ✨

- **API Integration:** Modern asynchronous functions for seamless product data fetching.
- **Sanity CMS:** Fully configured backend with validated and customized schemas.
- **Dynamic Frontend:** Real-time rendering of product data using modular Next.js components.
- **Error Handling:** Robust mechanisms for a smooth and user-friendly experience.

---

## Technologies Used 🛠️

- **Framework:** Next.js
- **CMS:** Sanity.io
- **Languages:** JavaScript, TypeScript
- **Database Testing:** Mock API

---

## Project Highlights 🏆

### **1. Fetching Data**

Efficient and scalable data fetching using Sanity CMS:

```javascript
import { client } from './lib/client';

export default async function FetchData() {
    const data = await client.fetch(`*[_type == 'product']`);
    return data;
}
```

### **2. Dynamic Rendering**

Render dynamic product listings with reusable Next.js components:

### **3. Data Migration**

Seamlessly migrate and populate your Sanity CMS:

- **Manual Import:** Import JSON or CSV data via Sanity's built-in tools.
- **Script-Based Migration:** Automate data population using Sanity’s client library.

---

## Live Project 🌐

Access the live demo here: [Premii Woods - Live](https://hail-shop.vercel.app/)

---

## License 📜

This project is licensed under the **MIT License**. Refer to the LICENSE file for more details.

---

**Crafted with ❤️ by Tayyab Ilyas (Student Leader) & the Premii Woods Team**

