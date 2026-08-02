# Web Tools Dashboard

A comprehensive collection of free, browser-based utility tools for developers, network administrators, and everyday users. All tools run locally in your browser with no data collection or external dependencies.

## 🎯 Overview

Web Tools Dashboard is a single-page application featuring multiple utilities designed to help you with common technical tasks. Whether you need to check your IP address, generate secure passwords, convert text to binary, or perform DNS lookups, all tools are available in one convenient location.

## 🛠️ Available Tools

### 1. **NS Lookup (DNS Records)**
- Query DNS records for any domain
- View A, AAAA, MX, NS, CNAME, and TXT records
- Tab-based navigation for filtering by record type
- Powered by Google DNS API

### 3. **Password Generator**
- Generate strong, secure passwords
- Customizable length (8-64 characters)
- Choose character types (uppercase, lowercase, numbers, symbols)
- Real-time password strength meter
- One-click copy to clipboard

### 4. **Screen Resolution**
- Display your monitor's resolution
- View available screen dimensions and device pixel ratio
- Aspect ratio calculation
- Estimated DPI
- Visual representation of your screen
- Auto-updates on resize and orientation changes

### 5. **Text ↔ Binary Converter**
- Convert text to 8-bit binary representation
- Convert binary (space/comma-separated) back to text
- Real-time conversion
- Character and bit counters
- Copy output to clipboard

### 6. **User Agent Identifier**
- Display your complete User Agent string
- Identify browser name and version
- Detect operating system and version
- Device type and model detection
- Rendering engine information
- Additional details: screen resolution, color depth, timezone, language, cookies status

### 7. **What is My IP?**
- Find your public IPv4 and IPv6 addresses
- View location information (city, country)
- Display ISP information
- Real-time IP detection
- Powered by reliable geolocation APIs

## ✨ Features

- **100% Browser-Based**: All tools run locally in your browser
- **No Data Collection**: Your data is never sent to external servers (except for API calls to public services)
- **Responsive Design**: Works on desktop, tablet, and mobile devices
- **Beautiful UI**: Consistent purple/blue gradient design with green accent boxes
- **Easy Navigation**: Organized dashboard with back buttons on all tools
- **Real-Time Updates**: Most tools update as you type or interact
- **Copy to Clipboard**: Quick copy buttons for easy sharing
- **No Dependencies**: Pure HTML/CSS/JavaScript, no heavy frameworks

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/yourusername/webtools.git
cd webtools
```

2. Open `index.html` in your web browser
3. Start using the tools!

No installation, build process, or server required. Just open and use!

## 📁 File Structure

```
webtools/
├── index.html                 # Main dashboard
├── asn-lookup.html           # ASN lookup tool
├── ns-lookup.html            # DNS records lookup
├── password-generator.html   # Password generator tool
├── screen-resolution.html    # Screen resolution checker
├── text-binary-converter.html # Text/Binary converter
├── user-agent.html           # User agent identifier
├── ip-address.html           # IP address lookup
└── README.md                 # This file
```

## 🎨 Design

- **Color Scheme**: 
  - Primary gradient: Purple (#667eea) to Blue (#764ba2)
  - Accent color: Green (#10b981)
  - Modern, clean design with smooth transitions

- **Layout**: 
  - Responsive grid layout on homepage
  - Centered containers with cards for each tool
  - Mobile-friendly design

## 🔒 Privacy & Security

- All tools are client-side only
- No user data is stored or transmitted (except for necessary API calls to public services)
- External APIs used: Google DNS API, ipify.org, geolocation-db.com, ip-api.com
- All operations are performed in your browser

## 🌐 Browser Compatibility

- Chrome/Chromium 90+
- Firefox 88+
- Safari 14+
- Edge 90+
- Works on modern mobile browsers

## 💡 Use Cases

- **Developers**: Check IP addresses, DNS records, screen resolution, and User Agent information
- **Network Admins**: Perform DNS lookups, ASN lookups, and IP geolocation
- **Security Professionals**: Generate secure passwords and analyze system information
- **General Users**: Quick access to commonly needed online tools

## 📝 License

This project is open source and available for free use and modification.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new tools
- Improve existing tools
- Enhance documentation

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Last Updated**: July 2026

