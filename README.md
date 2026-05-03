<img width="1885" height="907" alt="Screenshot 2026-05-03 091941" src="https://github.com/user-attachments/assets/85bffc3b-0d5e-4403-9133-d856474d90f4" />

Here’s a clean and professional **README.md** file for your project 👇 (you can directly copy–paste into your GitHub repo)

---

# 🛒 E-Commerce Cart System (JavaScript)

This is a simple **E-Commerce Product & Cart Management Web App** built using **HTML, Bootstrap, and Vanilla JavaScript**.

It allows users to:

* View products
* Add items to cart
* Increase/decrease quantity
* Remove items
* Calculate total price
* Add, update, and delete products

---

## 🚀 Features

### 🧾 Product Management

* Display product list dynamically
* Add new product
* Update existing product
* Delete product

### 🛍️ Cart System

* Add to cart
* Increase / Decrease quantity
* Remove item from cart
* Auto total calculation
* Checkout system

### 💾 Local Storage

* Cart data is stored in **localStorage**
* Data persists even after page reload

---

## 📂 Project Structure

```
project-folder/
│
├── index.html
├── style.css (optional)
├── script.js
└── README.md
```

---

## ⚙️ Technologies Used

* HTML5
* CSS3 / Bootstrap 5
* JavaScript (ES6)
* Browser LocalStorage API

---

## 🧠 How It Works

### 1. Product Display

* Products are stored in an array
* `showProduct()` dynamically renders product cards

### 2. Add to Cart

```js
addToCart(id)
```

* Checks if product already exists in cart
* If yes → increase qty
* If no → add new item

---

### 3. Cart Management

#### Increase Quantity

```js
increaseQty(id)
```

#### Decrease Quantity

```js
decreaseqty(id)
```

#### Remove Item

```js
remove(id)
```

---

### 4. Total Calculation

```js
total()
```

* Uses `reduce()` to calculate grand total

---

### 5. Checkout

```js
checkOut()
```

* If cart empty → alert
* Else → success message + clear cart

---

### 6. Add Product

```js
addProduct()
```

* Takes input from form
* Adds new product to array
* Updates UI instantly

---

### 7. Update Product

```js
UpdateProductModal(id)
```

* Opens modal
* Prefills product data
* Updates on submit

---

### 8. Delete Product

```js
DeleteProduct(id)
```

* Removes product from array
* Refresh UI

---

## ⚠️ Known Issues / Improvements

* ❗ Duplicate product IDs exist (`id: 27` appears twice)
* ❗ No validation for image URL
* ❗ No backend (data resets on refresh except cart)

---

## 🔮 Future Improvements

* Add backend (Node.js / MongoDB)
* User authentication
* Product categories & search
* Payment gateway integration
* Responsive UI enhancements

---

## ▶️ How to Run

1. Download or clone project
2. Open `index.html` in browser
3. Start using app

---

## 👨‍💻 Author

**Ankit Mor**

---

## 📌 Note

This project is built for **learning purpose** to understand:

* DOM manipulation
* Event handling
* LocalStorage
* CRUD operations in frontend

---

* convert this into **GitHub professional README (with badges)**
* or create **Node.js backend version** 🔥
