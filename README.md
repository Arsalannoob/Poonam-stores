# Poonam Stores - Premium Cosmetics India

## 🌟 Overview
Poonam Stores is a modern, professional e-commerce website for premium cosmetics in India. The website showcases product categories and includes two comprehensive contact forms:

1. **Product Enquiry Form** - For individual customers
2. **Wholesale & Bulk Orders Form** - For B2B/distributors

## 📁 Project Structure
```
poonam-stores/
├── index.html          # Main website (single page)
├── README.md          # This file
└── .gitignore        # Git ignore rules
```

## 🎨 Features

### Frontend
- ✅ Modern, minimalist design
- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Sticky navigation header
- ✅ Hero section with CTA
- ✅ Product categories showcase
- ✅ Dual contact forms with validation
- ✅ Local storage for form submissions
- ✅ Success/error messages
- ✅ Professional styling with gold accents

### Forms
1. **Form 1: Product Enquiry**
   - Name, Phone, Email, Message
   - For retail customers

2. **Form 2: Wholesale Orders**
   - Business Name, Phone, Email, Quantity/Type
   - For B2B inquiries
   - Direct contact information cards

## 🚀 Deployment Options

### Option 1: GitHub Pages (Free, Easiest)
1. Go to your repo settings → **Pages**
2. Select `main` branch as source
3. Your site: `https://Arsalannoob.github.io/poonam-stores`

### Option 2: Netlify (Free, With Forms)
1. Go to [netlify.com](https://netlify.com)
2. Connect GitHub repo
3. Deploy automatically
4. Enable Netlify Forms for backend submission

### Option 3: Custom Domain
- Connect your domain (e.g., poonamstores.com)
- Point DNS to hosting provider
- Upload files via FTP/Git

## 📝 Form Management

### Currently
- Forms save to browser's **localStorage**
- View submissions in browser console: `JSON.parse(localStorage.getItem('poonamSubmissions'))`

### To Add Backend (Next Steps)
1. **Add Netlify Forms**: Just add `netlify` attribute to forms
2. **Add Email Notifications**: Integrate with email service (SendGrid, Mailgun)
3. **Add Database**: Connect to Firebase, MongoDB, or PostgreSQL
4. **Create Admin Dashboard**: Manage submissions and inventory

## 🔧 Customization

### Update Contact Information
Edit `index.html` - Search for:
```html
<p>+91 XXXXX XXXXX<br>(Update with your number)</p>
<p>wholesale@poonamstores.com<br>enquiry@poonamstores.com</p>
```

### Change Colors
Edit CSS variables in `<style>` section:
- Gold accent: `#d4a373`
- Dark text: `#1a1a1a`
- Background: `#fdfbf7`

### Update Hero Image
Replace the Unsplash URL in `.hero` background

## 📊 Next Steps for Full Website

1. **Email Integration**
   - Connect to SendGrid/Mailgun
   - Auto-reply to customers

2. **Add Product Catalog**
   - Product pages with images
   - Shopping cart functionality

3. **Create Admin Panel**
   - Manage products
   - View & respond to inquiries
   - Inventory tracking

4. **Add Payment Gateway**
   - Razorpay (India)
   - PayPal
   - Stripe

5. **SEO & Analytics**
   - Google Analytics
   - Meta tags optimization
   - XML sitemap

## 📞 Support
For questions or modifications, contact via the website forms.

---

**Made with ❤️ for Poonam Stores**