# MATHIFY Repository

This repository contains two web applications:

## 1. Mathify - Math Problem Solver (index.html)

A step-by-step math problem solver supporting:
- Basic Arithmetic
- Linear Equations
- Quadratic Equations
- Algebraic Expressions
- Trigonometry
- Calculus (Limits, Differentiation, Integration)
- Linear Algebra
- Complex Numbers

**Access:** Open `index.html` in your browser

## 2. DataHub - Data Bundle Purchasing App (bundle-app.html)

A mobile-first web application for purchasing data/internet bundles across African countries.

### Features

- **Multi-Country Support:** 🇳🇬 Nigeria, 🇰🇪 Kenya, 🇬🇭 Ghana, 🇿🇦 South Africa, 🇹🇿 Tanzania, 🇺🇬 Uganda, 🇷🇼 Rwanda, 🇪🇬 Egypt
- **Network Providers:** MTN, Airtel, Vodacom, Safaricom, Glo, 9Mobile, Telkom, and more
- **Bundle Options:** 1GB to 50GB with various validity periods (1 day to 30 days)
- **Multiple Payment Methods:** 
  - 📱 Mobile Money (M-Pesa, MTN Mobile Money, etc.)
  - 💳 Debit Card
  - 🏦 Bank Transfer
  - 📞 USSD

### Supported Countries & Networks

#### Nigeria (NGN - ₦)
- MTN Nigeria
- Airtel Nigeria
- Glo Nigeria
- 9Mobile

#### Kenya (KES - KSh)
- Safaricom
- Airtel Kenya
- Telkom Kenya

#### Ghana (GHS - GH₵)
- MTN Ghana
- Vodafone Ghana
- AirtelTigo

#### South Africa (ZAR - R)
- Vodacom
- MTN South Africa
- Cell C

#### Tanzania (TZS - TSh)
- Vodacom Tanzania
- Airtel Tanzania
- Tigo Tanzania

#### Uganda (UGX - USh)
- MTN Uganda
- Airtel Uganda

#### Rwanda (RWF - FRw)
- MTN Rwanda
- Airtel Rwanda

#### Egypt (EGP - E£)
- Vodafone Egypt
- Orange Egypt
- Etisalat Egypt

### Bundle Packages

| Data | Validity | Example Price Range |
|------|----------|-------------------|
| 1GB  | 1 Day    | ₦300 - E£30      |
| 2GB  | 3 Days   | ₦500 - E£50      |
| 5GB  | 7 Days   | ₦1,200 - E£100   |
| 10GB | 30 Days  | ₦2,000 - E£180   |
| 20GB | 30 Days  | ₦3,500 - E£300   |
| 50GB | 30 Days  | ₦8,000 - E£600   |

### How to Use

1. Open `bundle-app.html` in your web browser
2. Select your country from the dropdown
3. Choose your network provider
4. Enter your phone number (format will be shown)
5. Select your desired data bundle
6. Click "Continue to Payment"
7. Review your order details
8. Select a payment method
9. Click "Pay Now" to complete your purchase

### Phone Number Formats

Each country has specific phone number formats:
- **Nigeria:** 080XXXXXXXX, 081XXXXXXXX, 070XXXXXXXX, etc.
- **Kenya:** 07XXXXXXXX, 01XXXXXXXX
- **Ghana:** 024XXXXXXXX, 054XXXXXXXX, 020XXXXXXXX
- **South Africa:** 082XXXXXXXX, 083XXXXXXXX, 061XXXXXXXX
- And more...

### Technical Details

- **Pure HTML/CSS/JavaScript** - No external dependencies
- **Mobile-First Design** - Optimized for smartphones
- **Responsive Layout** - Works on all screen sizes
- **Client-Side Validation** - Instant feedback on input
- **Modern UI** - Clean and intuitive interface

### Browser Compatibility

Works on all modern browsers:
- Chrome/Edge (recommended)
- Safari
- Firefox
- Opera

### Note

This is a demonstration application. In a production environment, you would need to:
1. Integrate with actual payment gateways (Paystack, Flutterwave, etc.)
2. Connect to network provider APIs
3. Implement backend services for order processing
4. Add user authentication
5. Set up database for transaction records
6. Implement security measures (HTTPS, data encryption, etc.)

## Getting Started

Simply open either HTML file in your web browser:
- For math problems: `index.html`
- For data bundles: `bundle-app.html`

No server or build process required!

## License

This project is available as-is for educational and demonstration purposes.
