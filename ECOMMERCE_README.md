# NutsSphere E-Commerce Website

## 🌰 A Complete E-Commerce Platform for Premium Superfoods

Welcome to NutsSphere - your one-stop destination for premium organic nuts, seeds, dried fruits, and superfoods!

---

## ✨ Features

### 🛍️ **E-Commerce Functionality**

#### Shopping Experience
- **Product Catalog**: Browse through a curated selection of premium products
- **Product Filtering**: Filter by category (Nuts, Seeds, Dried Fruits, Superfoods)
- **Quick View**: View product details in a modal without leaving the page
- **Product Variants**: Multiple size options for each product
- **Stock Management**: Real-time stock status display
- **Wishlist**: Save products for later (coming soon)

#### Shopping Cart
- **Add to Cart**: Seamlessly add products to your cart
- **Cart Sidebar**: Slide-out cart with full details
- **Quantity Management**: Increase/decrease quantities
- **Remove Items**: Easy item removal
- **Price Calculation**: Automatic subtotal, shipping, and total calculation
- **Free Shipping**: On orders above ₹1000
- **Persistent Cart**: Cart saved in browser storage

#### User Authentication
- **Login System**: Secure user login
- **Registration**: Create new account
- **Guest Checkout**: Option to checkout as guest
- **Profile Management**: Update personal information
- **Password Reset**: Forgot password functionality

#### Checkout Process
- **Multi-Step Checkout**: 3-step checkout flow
  - Step 1: Shipping Address
  - Step 2: Payment Method
  - Step 3: Order Confirmation
- **Multiple Payment Options**:
  - Cash on Delivery (COD)
  - UPI Payment
  - Credit/Debit Card
  - Net Banking
- **Address Management**: Save and manage multiple addresses
- **Order Summary**: Real-time order summary during checkout

#### Order Management
- **Order Placement**: Complete order processing
- **Order History**: View all past orders
- **Order Tracking**: Track order status
- **Order Status**: Real-time status updates
  - Pending
  - Processing
  - Shipped
  - Delivered
  - Cancelled

#### User Dashboard
- **My Orders**: View order history and status
- **Profile**: Manage personal information
- **Addresses**: Manage shipping addresses
- **Wishlist**: View saved items

### 🎨 **Design Features**

#### Modern UI/UX
- **Responsive Design**: Works perfectly on all devices
- **Smooth Animations**: CSS animations and transitions
- **Loading States**: Loading indicators for better UX
- **Toast Notifications**: Real-time feedback
- **Modal Dialogs**: Clean modal interfaces
- **Sticky Navigation**: Always accessible navigation
- **Back to Top**: Quick scroll to top button

#### Visual Elements
- **Hero Section**: Engaging landing page with animated stats
- **Product Cards**: Beautiful product presentations
- **Color Scheme**: Professional orange and green palette
- **Typography**: Modern Poppins and Playfair Display fonts
- **Icons**: Font Awesome icons throughout
- **Shadows & Depth**: Material design principles
- **Hover Effects**: Interactive elements

### 📱 **Mobile Features**
- **Hamburger Menu**: Mobile-friendly navigation
- **Touch Optimized**: Touch-friendly buttons and controls
- **Responsive Grid**: Adaptive product layouts
- **Mobile Cart**: Full-screen cart on mobile
- **Mobile Checkout**: Optimized checkout flow

### 🔒 **Security & Performance**
- **Local Storage**: Secure browser storage for cart and user data
- **Input Validation**: Form validation on all inputs
- **Error Handling**: Graceful error management
- **Fast Loading**: Optimized CSS and JavaScript
- **SEO Friendly**: Proper meta tags and semantic HTML

### 💬 **Communication**
- **Contact Form**: Get in touch form
- **WhatsApp Integration**: Direct WhatsApp chat button
- **Newsletter Signup**: Email subscription
- **Social Media Links**: Connect on all platforms
- **Email Support**: sohanankulwar@gmail.com
- **Phone Support**: +91 7038979754

### 📦 **Product Information**
- **High-Quality Images**: Product photos
- **Detailed Descriptions**: Full product information
- **Pricing**: Current price, original price, and discount
- **Features Tags**: Highlight key features
- **Quality Badges**: Premium quality indicators
- **Stock Status**: In-stock/Out-of-stock display

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs completely in the browser!

### Installation
1. Clone or download the repository
2. Open `index.html` in your web browser
3. Start shopping!

### File Structure
```
nutsphere/
├── index.html          # Main HTML file
├── styles.css          # Complete CSS styles
├── script.js           # JavaScript functionality
├── README.md           # This file
└── images/             # Product and brand images
    ├── final_nutsphere_logo_01-removebg-preview.png
    ├── pistachos.jpg
    ├── almonds.jpg
    ├── cashews.jpg
    ├── walnuts.jpg
    └── black_rasins.jpg
```

---

## 💻 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with:
  - CSS Variables
  - Flexbox & Grid
  - Animations & Transitions
  - Media Queries
- **JavaScript (ES6+)**:
  - DOM Manipulation
  - Event Handling
  - Local Storage API
  - Async Operations
- **Font Awesome**: Icon library
- **Google Fonts**: Poppins & Playfair Display

---

## 🎯 How to Use

### For Customers

#### Shopping
1. Browse products on the homepage
2. Click on products to view details
3. Use filters to find specific categories
4. Add products to cart with quantity selection
5. View cart by clicking the cart icon

#### Checkout
1. Click "Proceed to Checkout" in cart
2. Login or register (or continue as guest)
3. Enter shipping address
4. Select payment method
5. Review order and confirm
6. Receive order confirmation

#### Account Management
1. Click on "Account" in navigation
2. Login or register
3. Access dashboard for:
   - Order history
   - Profile updates
   - Saved addresses
   - Wishlist

#### Order Tracking
1. Go to dashboard → My Orders
2. Click "Track Order" on any order
3. View real-time order status

### For Developers

#### Adding Products
Edit the `productsData` array in `script.js`:

```javascript
{
    id: 'product-id',
    name: 'Product Name',
    category: 'nuts', // or 'seeds', 'dried-fruits', 'superfoods'
    description: 'Product description',
    image: 'images/product.jpg',
    price: 499,
    originalPrice: 599,
    discount: 17,
    variants: [
        { size: '250g', price: 499 },
        { size: '500g', price: 949 }
    ],
    features: ['Feature 1', 'Feature 2'],
    badges: ['Premium Quality', 'Organic'],
    inStock: true
}
```

#### Customizing Styles
Colors are defined in CSS variables at the top of `styles.css`:

```css
:root {
    --primary-color: #E65100;
    --secondary-color: #2E7D32;
    /* ... more colors */
}
```

#### Modifying Functionality
Key functions in `script.js`:
- `addToCart(productId)` - Add items to cart
- `proceedToCheckout()` - Start checkout
- `placeOrder()` - Complete order
- `trackOrder(orderId)` - Track order status

---

## 🎨 Color Palette

- **Primary Orange**: #E65100 - Main brand color
- **Primary Dark**: #BF360C - Hover states
- **Secondary Green**: #2E7D32 - Success/Organic
- **Accent Blue**: #42A5F5 - Information
- **Cream**: #FFF8DC - Background
- **Charcoal**: #212121 - Text

---

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

---

## 🌟 Key Highlights

✅ **100% Client-Side** - No backend required  
✅ **Fully Responsive** - Works on all devices  
✅ **Modern Design** - Clean and professional  
✅ **Complete E-Commerce** - Full shopping experience  
✅ **User-Friendly** - Intuitive interface  
✅ **Fast Performance** - Optimized code  
✅ **SEO Optimized** - Search engine friendly  
✅ **Accessible** - WCAG compliant  

---

## 🔄 Data Persistence

All data is stored in browser's localStorage:
- **Cart**: Persists across sessions
- **User**: Login state maintained
- **Orders**: Order history saved
- **Wishlist**: Saved items stored

---

## 🚧 Future Enhancements

- [ ] Backend integration
- [ ] Real payment gateway
- [ ] Product reviews and ratings
- [ ] Advanced search functionality
- [ ] Product recommendations
- [ ] Email notifications
- [ ] SMS notifications
- [ ] Multi-language support
- [ ] Currency converter
- [ ] Loyalty program
- [ ] Referral system
- [ ] Blog section
- [ ] Recipe section

---

## 📞 Support

**Email**: sohanankulwar@gmail.com  
**Phone**: +91 7038979754  
**WhatsApp**: [Chat with us](https://wa.me/917038979754)  
**Location**: Nanded, Maharashtra, India

---

## 📄 License

© 2025 NutsSphere. All rights reserved.

---

## 👨‍💻 Developer Notes

### Testing Accounts
For testing purposes, any email/password combination will work for login.

### Sample Orders
Orders are automatically created with status "pending" and can be tracked through the dashboard.

### Payment Testing
All payment methods are currently for demonstration purposes only. No real transactions are processed.

---

## 🙏 Acknowledgments

- Font Awesome for icons
- Google Fonts for typography
- Inspiration from modern e-commerce platforms

---

## 📈 Version History

### Version 1.0.0 (Current)
- Initial release
- Complete e-commerce functionality
- User authentication
- Shopping cart
- Checkout process
- Order management
- Responsive design
- Mobile optimization

---

**Built with ❤️ for health-conscious customers**

*"Pure Goodness in Every Bite"* - NutsSphere