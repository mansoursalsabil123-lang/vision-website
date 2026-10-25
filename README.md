# VISION STORE 👗

**VISION STORE** is a modern online fashion store based in Tunisia. It allows customers to explore a clothing collection, view product details, select sizes and colors, and place orders online. The website also includes an administration interface for managing products, stock, store information, and customer orders.
https://vision-store-d1477.web.app
## ✨ Features

### 🛍️ Customer Interface
<img width="1900" height="891" alt="home" src="https://github.com/user-attachments/assets/3b53dfba-eb48-4a8f-a645-fe535d93fa0c" />
<img width="1897" height="902" alt="items" src="https://github.com/user-attachments/assets/e7d4c14c-d510-49b0-9710-c3e5ac647eae" />
<img width="707" height="837" alt="your bag" src="https://github.com/user-attachments/assets/c2741e85-95af-4cb1-b579-6787caefadd1" />


- Browse the available clothing collection.
- Filter products by category: tops, bottoms, and outerwear.
- View product photos and switch between colors and images.
- Select available sizes and check stock availability.
- Add products to the shopping bag.
- View the order total.
- Place orders by providing delivery information.
- Select a governorate and city in Tunisia.
- Switch between English, French, and Arabic interface options.

### 🔐 Administration Interface
<img width="1122" height="836" alt="admin tab" src="https://github.com/user-attachments/assets/65c5d341-6900-4424-b681-b8b089efa6b5" />

- Access the administration studio using an access code.
- Add, edit, and delete products.
- Manage product prices, categories, descriptions, sizes, and stock.
- Add product colors and upload photos.
- Update the store name, description, contact details, and main image.
- View customer orders and their details.

### ⚙️ Technologies Used
- **HTML5** — Website structure.
- **CSS3** — Styling and responsive design.
- **JavaScript** — Website functionality and interactions.
- **Firebase Realtime Database** — Store products, inventory, settings, and orders.
- **Cloudinary** — Upload and store product images.
- **EmailJS** — Send order-related emails.
- **Google Fonts** — Typography.
- **Unsplash** — Main collection image.

## 📁 Project Structure

```text
VISION-STORE/
├── index.html          # Main website page
├── style.css           # Website styles
├── app.js              # Main application logic
├── README.md           # Project documentation
├── .firebaserc         # Firebase project configuration
└── .gitignore          # Git ignored files
```

## 🚀 Installation and Setup

### 1. Download the project
Clone the repository or download the project files to your computer.

### 2. Configure Firebase
The application uses Firebase Realtime Database to store and retrieve information.

Make sure the Firebase project is configured correctly and that the database rules allow the required operations.

### 3. Configure Cloudinary
Cloudinary is used to upload product photos.

Configure the cloud name and upload preset in `app.js` according to your Cloudinary account.

### 4. Configure EmailJS
To enable order-related email notifications, configure the following values in `app.js`:

- Public Key
- Service ID
- Template ID

Without this configuration, orders may still be saved, but email notifications will not be sent.

### 5. Run the website
Open the project in Visual Studio Code and launch `index.html` using the Live Server extension, or deploy the website using Firebase Hosting.

## 🛒 How to Use the Website

1. Open the website.
2. Browse the available products.
3. Choose a color and size.
4. Click **ADD TO BAG**.
5. Open the shopping bag.
6. Enter your contact and delivery information.
7. Confirm the order.

After a successful order, the system saves the order in Firebase and updates the available stock.

## 🔑 Administration

To access the administration interface:

1. Click **ADMIN** in the footer.
2. Enter the configured administration access code.
3. Choose the section you want to manage:
   - **Products:** Manage the collection and inventory.
   - **Store Settings:** Update the store identity and contact information.
   - **Orders:** View customer orders.

**Security note:** The current application uses a client-side access code. For a production website, implement Firebase Authentication and appropriate database security rules to protect administrative functions and customer data.

## 🌐 Deployment

The project can be deployed using Firebase Hosting.

Typical deployment commands, after installing the Firebase CLI and signing in, are:

```bash
npm install -g firebase-tools
firebase login
firebase init hosting
firebase deploy
```

During setup, select the correct Firebase project and configure the public directory to match the location of your website files.

## 📌 Important Notes

- A working internet connection is required for Firebase, Cloudinary, Google Fonts, and EmailJS services.
- Firebase database rules and service configurations must be set up correctly.
- Product images require a valid Cloudinary configuration.
- Email notifications require valid EmailJS credentials and templates.
- Administrative access should be secured before the website is used in production.

##  Project Information

**Project Name:** VISION STORE  
**Type:** E-commerce website  
**Location:** Tunisia  
**Purpose:** Online fashion shopping and inventory management
## 👩‍💻 Author

Salsabil Mansour

Computer Science Student | ISSAT Sousse
---

*VISION STORE — Wear your vision.*
