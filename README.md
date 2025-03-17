# plutonium17.github.io
# 🌐 Product Catalogue Application  

## 📌 Overview  
The **Product Catalogue Application** is a **cloud-based** web application that allows users to **add new products** and **search for existing products**. The system is built using **Flask (Python) for the backend**, **Azure SQL Database for storage**, and **HTML, CSS, and JavaScript for the frontend**. It is deployed on **Microsoft Azure App Service**, ensuring **scalability, security, and high availability**.

---

## 📜 Features  
✅ **Add a New Product**: Users can enter a product name, price, and description to store in the database.  
✅ **Search for a Product**: Users can search for products by name, retrieving relevant results dynamically.  
✅ **Cloud-Based Deployment**: The app is hosted on **Azure App Service**, making it accessible from anywhere.  

---

## 🏗️ Architecture Diagram  

```mermaid
graph TD;
    A[User (Web Browser)] -->|HTTP Request| B[Flask Backend API];
    B -->|Store/Retrieve Data| C[Azure SQL Database];
    C -->|Data Response| B;
    B -->|JSON Response| A;
