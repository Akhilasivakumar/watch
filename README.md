 # Watch Shopping Cart Website
This is a JavaScript-based shopping cart website for watches.
Users can browse men’s and women’s watches, filter by brand, add products to the cart, and view the total price.
An admin dashboard is included to manage products using a JSON database.

## Features
- Men’s and Women’s watch sections
- Brand-wise filtering
- Add to cart and remove from cart
- Cart total calculation
- Admin dashboard for product management
- JSON-based data storage
- Responsive UI
## Tech Stack
- HTML5
- CSS3
- JavaScript (ES6)
- JSON (db.json)
## ## JSON Server Setup (Local Development)

This project uses **JSON Server** to simulate a backend during local development.  
JSON Server is used only for testing API calls and CRUD operations.  
It is **not used in the deployed (Netlify) version**.

### Commands
npm install -g json-server --force
json-server --version 
 npx json-server --watch db.json --port 3000
 > ⚠️ Note: Do not open HTML files by double-clicking.  
> Always use Live Server to avoid server and fetch errors.

---

## How to Run the Project

### Run Locally
1. Clone the repository  
2. Open the project folder in VS Code  
3. Install the **Live Server** extension in VS Code  
4. Right-click on `index.html` and select **Open with Live Server**




