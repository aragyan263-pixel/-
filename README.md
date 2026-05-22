# پاسکیلی ئالان - Alan Bike

A responsive bike e-commerce website built with HTML, CSS, and JavaScript.

## Features

✨ **Features:**
- 🚲 Product showcase with images and pricing
- 💬 WhatsApp integration for customer inquiries
- 🔐 Admin panel with password protection
- ➕ Add new products dynamically
- 🗑️ Delete products (admin only)
- 💾 LocalStorage for data persistence
- 📱 Fully responsive design
- 🌙 RTL support for Kurdish language

## Admin Panel

**Password:** `alan123`

### Admin Features:
1. Click the "🛠 پانێڵی بەڕێوەبەر" button in the header
2. Enter the admin password
3. Add new bikes with:
   - Product name
   - Price (in USD)
   - Image URL
4. Delete existing products

## WhatsApp Integration

- Customers can request bikes via WhatsApp
- Default WhatsApp number: `9647501851817` (Iraq)
- To change, edit the `MY_WHATSAPP` constant in the HTML file

## Customization

### Change Admin Password:
```javascript
const ADMIN_PASSWORD = "your_new_password";
```

### Change WhatsApp Number:
```javascript
const MY_WHATSAPP = "your_whatsapp_number";
```

## Deployment

This website is ready to deploy on:
- **GitHub Pages** - Enable in repository settings
- **Netlify** - Connect your GitHub repo
- **Vercel** - Sync with your repository
- Any static hosting service

## Technologies Used

- HTML5
- CSS3
- Vanilla JavaScript
- LocalStorage API
- WhatsApp Web API

## License

© 2026 پاسکیلی ئالان - All rights reserved.

---

**Language:** Central Kurdish (Sorani)
**Direction:** Right-to-Left (RTL)