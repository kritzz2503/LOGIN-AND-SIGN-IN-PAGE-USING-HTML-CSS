# 🔐 Glassmorphism Login & Sign In Pages

A simple and modern **Login Page and Sign In Page** designed using **HTML and CSS** with a **Glassmorphism-inspired UI**.

This project was created to practice and understand fundamental frontend development concepts such as **CSS gradients, Flexbox, form design, input styling, buttons, hover effects, active states, and responsive layout concepts**.

## 📌 Project Overview

This project contains two separate webpage designs:

### 1. Login Page

A stylish login interface where users can enter their login credentials. The page uses a modern gradient background and a glass-like form design.

### 2. Sign In Page

A simple sign-in form containing username and password fields along with **Sign In** and **Cancel** buttons. It uses a Glassmorphism-inspired visual style with CSS effects.

## ✨ Features

* 🎨 Modern gradient background
* 🪟 Glassmorphism-inspired form design
* 📱 Clean and simple user interface
* 📝 Username and password input fields
* 🔘 Sign In and Cancel buttons
* 🖱️ Button hover effects
* 👆 Button active effects
* 📦 Box shadow effects
* 📐 Flexbox-based layout
* 🎨 Transparent input backgrounds
* 🔤 Custom font styling

## 🛠️ Technologies Used

* **HTML5** – Used to create the structure of the webpages.
* **CSS3** – Used for styling, gradients, Flexbox layout, shadows, transparency, and interactive button effects.

## 📂 Project Structure

```text
Glassmorphism-Login-Page/
│
├── login.html
├── signin.html
└── README.md
```

## 🎨 Design Concepts Practiced

### Linear Gradient

The background uses a linear gradient to create a smooth transition between two colors.

```css
background: linear-gradient(to right, rgb(15, 54, 15), rgb(184, 184, 22));
```

### Flexbox

Flexbox is used to align the form and arrange the buttons horizontally.

```css
display: flex;
justify-content: center;
align-items: center;
```

### Transparent Inputs

The input fields use a transparent background and bottom border to create a minimal design.

```css
background: transparent;
border: none;
border-bottom: 1px solid rgba(225, 225, 225, 0.8);
```

### Box Shadow

Box shadows are used to add depth to the form and buttons.

```css
box-shadow: 5px 5px 5px 5px rgb(220, 217, 163);
```

### Hover and Active Effects

Buttons change their appearance when the user moves the mouse over them or clicks them.

```css
button:hover {
    background-color: grey;
}

button:active {
    background-color: white;
}
```

## 🚀 How to Run

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `login.html` to open the Login Page.
4. Open `signin.html` to view the Sign In Page.

You can also open the HTML files using **Visual Studio Code** and run them with the **Live Server** extension.

## 📚 Learning Goals

Through this project, I practiced:

* HTML forms
* Input fields and labels
* CSS gradients
* Glassmorphism design concepts
* CSS Flexbox
* Box shadows
* Transparency using `rgba()`
* Button styling
* `:hover` pseudo-class
* `:active` pseudo-class
* Basic webpage layout

## 🔮 Future Improvements

* Add JavaScript form validation
* Add a **Show/Hide Password** feature
* Add a **Forgot Password** link
* Add a **Remember Me** checkbox
* Make the design fully responsive
* Add background images and decorative elements
* Connect the forms to a backend
* Store user details in a database
* Add user authentication

## 👩‍💻 Author

**Krithika Subramanian**

This project is created as part of my frontend development learning journey to practice **HTML and CSS** and explore modern UI design using **Glassmorphism**.
