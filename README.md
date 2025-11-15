# Web_apps
# Maxcart (E-commerce Homepage Clone)

This is a front-end web project that clones the homepage of an e-commerce website like Flipkart. It is built using HTML, CSS, and the Bootstrap 4 framework to create a responsive and modern-looking online shopping site interface. The project includes a main homepage and a separate login page.

## 🎯 Purpose

The main purpose of this project is to demonstrate and practice front-end web development skills, specifically:
* **HTML5:** Structuring the web pages (navbar, carousels, product cards, footer).
* **CSS3:** Applying custom styles, overriding Bootstrap defaults, and creating a unique visual theme (e.g., custom colors, backgrounds, and spacing).
* **Bootstrap 4:** Utilizing a CSS framework for responsive design, grid layout, and pre-built components like carousels, cards, and navbars.

This project serves as a portfolio piece to showcase the ability to build a complex, responsive layout from scratch.

## ✨ How It Works (Features)

The project consists of two main pages:

### 1. Home Page (`flipkart.html`)
* **Responsive Navbar:** A sticky navigation bar at the top with the brand name "MAXCART," a search bar, login/signup links, a "More" dropdown, and a "Cart" icon.
* **Main Carousel:** A large, auto-sliding image carousel for showcasing main promotions and banners.
* **Deals of the Day:** A dedicated section that features a nested carousel. This carousel displays product "cards" with an image, title, description, and "Buy" button.
* **Static Image Grid:** A simple grid layout below the main content to display other categories or offers.
* **Detailed Footer:** A comprehensive, multi-section footer replicating a real e-commerce site, including links for Help, policies, contact information, and social media.

### 2. Login Page (`login.html`)
* **Separate Login Form:** A clean, centered login page with a custom gradient background and a simple form for "Username" and "Password."
* **Custom Styling:** The page uses a mix of external (`flipkart.css`) and internal (`<style>` tag) CSS for a unique, animated appearance.

## 🚀 How to Run This Project

This is a static website and does not require any backend or special server to run.

### Prerequisites
* A modern web browser (like Google Chrome, Firefox, or Microsoft Edge).
* A code editor (like VS Code) if you wish to modify the code.

### Running the Project
1.  **Download or Clone the Repository:**
    ```bash
    git clone [YOUR_GITHUB_REPOSITORY_URL]
    ```
    (Or, you can download the project as a ZIP file and extract it.)

2.  **Ensure File Structure:**
    This project relies on external files. Make sure your folder structure is correct. You will need:
    * `flipkart.html`
    * `login.html`
    * `flipkart.css`
    * `script.js` (Note: This file was referenced in the HTML but not provided. Functionality like carousel sliding and login form submission may not work without it.)
    * An `images` folder (Note: This folder was referenced for all product and carousel images but was not provided. The site will display broken images until you add your own images to this folder.)

3.  **Open in Browser:**
    Navigate to the project folder and simply **double-click the `flipkart.html` file**. It will open directly in your default web browser. You can navigate to the login page by clicking the "Login & Sign-up" link in the navbar.

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **Bootstrap 4.1** (for grid, components, and responsive layout)
* **Font Awesome 5.0** (for icons in the navbar and footer)
* **JavaScript** (linked as `script.js` for dynamic features like carousels and form handling)
