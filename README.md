# PhoneHub - Online Phone Sales Website

A modern, responsive e-commerce website for selling smartphones built with HTML5, CSS3, JavaScript, and Bootstrap. Perfect for student projects and learning web development.

## 🌟 Features

### Pages Included
1. **Home Page (index.html)** - Beautiful landing page with product showcase
2. **Contact Page (contact.html)** - Contact form with validation and message history
3. **Login Page (login.html)** - Secure login with form validation
4. **Register Page (register.html)** - User registration with comprehensive validation
5. **Profile Page (profile.html)** - User account management and order history
6. **Shopping Cart (cart.html)** - Full-featured shopping cart with checkout

### Key Features
- ✅ **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- ✅ **localStorage Integration** - All data persists in browser storage
- ✅ **Form Validation** - Comprehensive JavaScript validation on all forms
- ✅ **Modern UI/UX** - Beautiful gradient designs and smooth animations
- ✅ **Bootstrap 5** - Professional responsive framework
- ✅ **Font Awesome Icons** - Beautiful icons throughout the site
- ✅ **Shopping Cart** - Add, remove, and manage products
- ✅ **User Authentication** - Login and registration system
- ✅ **Profile Management** - View and edit user information
- ✅ **Order History** - Track user orders
- ✅ **Promo Codes** - Support for discount codes
- ✅ **Contact Management** - Store and manage customer inquiries

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor or IDE (VS Code recommended)
- Git for version control

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/phonehub.git
   cd phonehub
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Python 2
   python -m SimpleHTTPServer 8000
   
   # Using Node.js (if http-server is installed)
   http-server
   ```

3. **Access the website**
   - Navigate to `http://localhost:8000` in your browser

## 📋 Demo Credentials

For testing the login functionality:
- **Email:** demo@phonehub.com
- **Password:** Demo123

## 💾 Data Storage

All data is stored in browser localStorage:
- **Users** - Registration and login data
- **Cart** - Shopping cart items
- **Orders** - Purchase history
- **Contact Messages** - Customer inquiries
- **Login History** - User login records

**Note:** Data persists only in the same browser. Clearing browser data will erase all stored information.

## 🎨 Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Advanced styling with gradients, animations, and flexbox
- **JavaScript** - Form validation, localStorage management, DOM manipulation
- **Bootstrap 5** - Responsive grid and components
- **Font Awesome 6** - Icon library

## 📱 Responsive Breakpoints

- Mobile: < 576px
- Tablet: 576px - 768px
- Desktop: > 768px

## 🔐 Form Validation

### Login Form
- Email validation
- Password minimum 6 characters
- Remember me functionality

### Registration Form
- First/Last name validation (minimum 2 characters)
- Valid email format
- Password strength meter
- Password confirmation
- Phone number validation (10+ digits)
- Address and city validation
- Terms agreement required

### Contact Form
- Name validation (minimum 2 characters)
- Valid email required
- Phone number optional but validated if provided
- Subject and message required
- Message minimum 10 characters

## 🛒 Shopping Features

- **Add to Cart** - Easy product addition
- **Quantity Management** - Adjust quantities in cart
- **Remove Items** - Delete products from cart
- **Shipping Options** - Multiple delivery methods
- **Promo Codes** - Apply discount codes:
  - SAVE10: $10 discount
  - SAVE20: $20 discount
  - WELCOME5: $5 discount
  - SUMMER15: $15 discount
- **Order Summary** - Real-time total calculation
- **Subtotal, Shipping & Tax** - Transparent pricing

## 👤 User Profile Features

- View account information
- Edit profile details
- View order history
- Login history tracking
- Logout functionality
- Account management

## 📧 Contact Management

- Contact form submission
- Message validation
- Contact information display
- Message history storage
- Clear message history option

## 🚀 Deployment to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New" to create a new repository
3. Name it: `phonehub` (or your preferred name)
4. Choose "Public"
5. Initialize with README (optional, we already have one)
6. Click "Create repository"

### Step 2: Initialize Git and Push Code
```bash
cd path/to/phonehub

# Initialize git repository
git init

# Add all files
git add .

# Create initial commit
git commit -m "Initial commit: PhoneHub e-commerce website"

# Add remote repository
git remote add origin https://github.com/yourusername/phonehub.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" (gear icon)
3. Scroll to "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"
6. Your site will be published at: `https://yourusername.github.io/phonehub/`

### Step 4: Update Links (if needed)
If your site is in a subdirectory, ensure all links work correctly.

## 📚 File Structure

```
phonehub/
├── index.html          # Home page
├── contact.html        # Contact page
├── login.html          # Login page
├── register.html       # Registration page
├── profile.html        # User profile page
├── cart.html           # Shopping cart page
├── .gitignore          # Git ignore file
├── README.md           # Project documentation
└── LICENSE             # MIT License
```

## 🎓 Learning Outcomes

By studying this project, you'll learn:
- HTML5 semantic structure
- CSS3 styling and animations
- JavaScript DOM manipulation
- Form validation techniques
- localStorage API usage
- Responsive design principles
- Bootstrap framework
- Git and GitHub workflows

## 🐛 Troubleshooting

### localStorage Not Working?
- Check if your browser allows localStorage
- Try in incognito/private mode
- Ensure JavaScript is enabled

### Forms Not Validating?
- Ensure JavaScript is enabled
- Check browser console for errors (F12)
- Clear browser cache and reload

### Responsive Design Issues?
- Clear browser cache
- Check viewport meta tag (included in HTML)
- Test in different browsers

## 📝 Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔄 Updates and Improvements

Future enhancements could include:
- Payment gateway integration
- Backend API integration
- Email verification
- Password reset functionality
- Product filtering and search
- User reviews and ratings
- Admin dashboard
- Inventory management

## 📄 License

This project is open source and available under the MIT License.

## 👨‍💻 Author

Created for educational purposes. Perfect for students learning web development!

## 🤝 Contributing

Feel free to fork this project and submit pull requests for improvements.

## 📞 Support

For issues or questions:
1. Check the troubleshooting section
2. Review the code comments
3. Check browser console for errors (F12)

---

**Happy Coding! 🚀**

This project is a great starting point for learning full-stack web development concepts. Enjoy building and customizing!
