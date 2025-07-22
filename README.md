E-Commerce Storefront

A modern, minimalistic e-commerce storefront built with HTML, CSS, and JavaScript, featuring product browsing, cart functionality, admin product management, and separate admin/customer login forms. The application uses localStorage for data persistence and a premium blue color scheme with the Inter font for a sleek UI.

Features

Product Listing (index.html): Browse products with search and filter options (category, price, rating). Filters are preserved in the URL for easy sharing.

Product Details (product.html): View detailed product information with a filter bar to return to filtered results.

Shopping Cart (cart.html): Add/remove items (customer-only), view total price, and proceed to checkout if the cart is not empty.

Order Confirmation (order.html): Displays a confirmation message after checkout and clears the cart.

Admin Dashboard (admin.html): Create, update, and delete products (admin-only), with changes saved to localStorage.

Login System (login.html): Separate forms for admin (admin/admin123) and customer (customer/customer123) logins, controlling access to features.

Responsive Navbar: Embedded in all pages, displaying login status, cart count, and navigation links (Products, Cart, Admin, Login). No scrollbars due to fixed height and optimized CSS.

Data Storage: Uses localStorage to store products ("products"), cart items ("cart"), and user login details ("user").

UI Design: Premium blue palette (#1E3A8A, #3B82F6, #F1F5F9), Inter font, rounded corners, and smooth hover transitions for a modern look.
