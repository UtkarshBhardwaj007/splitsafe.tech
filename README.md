# SplitSafe - Blockchain-Powered Bill Splitting Platform

A modern, minimalist landing page for SplitSafe - the first blockchain-based bill splitting platform with instant stablecoin settlements and consensus-based expense tracking.

## 🚀 Features

- **Consensus-Based Approval**: Every expense requires approval from all involved parties
- **Instant Stablecoin Settlement**: Settle debts instantly with USDC or USDT
- **Immutable Transaction History**: All transactions recorded on the blockchain
- **Modern Minimalist Design**: Clean, responsive UI with smooth animations
- **Mobile-First Approach**: Fully responsive across all devices

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid, Flexbox, and CSS Variables
- **Vanilla JavaScript**: Lightweight interactions without dependencies
- **GitHub Pages**: Static site hosting with custom domain

## 📁 Project Structure

```
splitsafe.tech/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
├── CNAME              # Custom domain configuration
├── README.md          # Project documentation
├── .gitignore         # Git ignore file
└── assets/            # Logo and image assets
    ├── logo-color.svg
    ├── logo-grayscale.svg
    └── ...
```

## 🌐 GitHub Pages Setup

### 1. Create GitHub Repository

1. Create a new repository on GitHub
2. Clone the repository locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/splitsafe.tech.git
   cd splitsafe.tech
   ```

### 2. Push Code to GitHub

```bash
git add .
git commit -m "Initial commit - SplitSafe landing page"
git push origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on **Settings** → **Pages**
3. Under **Source**, select **Deploy from a branch**
4. Choose **main** branch and **/ (root)** folder
5. Click **Save**

### 4. Configure Custom Domain

#### On GitHub:
1. The CNAME file is already included with `splitsafe.tech`
2. GitHub will automatically detect and configure it

#### On Your Domain Provider:
Add the following DNS records:

**Option A - Using A Records (Recommended):**
```
Type: A
Name: @
Value: 185.199.108.153

Type: A
Name: @
Value: 185.199.109.153

Type: A
Name: @
Value: 185.199.110.153

Type: A
Name: @
Value: 185.199.111.153
```

**Option B - Using CNAME Record:**
```
Type: CNAME
Name: www
Value: YOUR_USERNAME.github.io
```

### 5. Enable HTTPS

1. Wait for DNS propagation (can take up to 24 hours)
2. In GitHub Pages settings, check **Enforce HTTPS**

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #1f0f53;    /* Dark blue */
    --accent-color: #ffdb99;      /* Peach */
    --text-dark: #1a1a1a;
    --text-light: #666666;
}
```

### Content
- Update text content in `index.html`
- Replace placeholder IconScout URLs with your premium assets
- Modify email form action to connect to your backend

### Icons
The landing page uses IconScout premium assets. Replace the placeholder URLs with your actual premium asset URLs from IconScout.

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🔧 Local Development

To run locally, simply open `index.html` in your browser or use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

## 📄 License

This project is proprietary to SplitSafe. All rights reserved.

## 🤝 Contributing

For any updates or modifications, please create a pull request or contact the development team.

---

Built with ❤️ for the future of shared expenses 
