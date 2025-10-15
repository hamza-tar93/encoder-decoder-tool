# 🔐 Encoder/Decoder Tool

Client-side encoder/decoder tool with hash identification and Caesar cipher analysis. Essential utility for penetration testers and security researchers. No data leaves your browser.

# 🌐 Live Demo

**[Try it here](https://hamza-tar93.github.io/encoder-decoder-toolkit/)**

## ✨ Features

### Text Transformations
- **URL Encoding/Decoding** - Handle URL-encoded parameters
- **Base64 Encoding/Decoding** - Work with Base64 encoded data
- **HTML Entity Encoding/Decoding** - Convert special characters (XSS testing)
- **ASCII Hex Encoding/Decoding** - Hexadecimal representation
- **Binary Encoding/Decoding** - Binary data conversion
- **Octal Encoding/Decoding** - Octal representation

### Encoding Depth
- Single encode/decode
- Double encode/decode (for bypass techniques)

### Cryptographic Analysis
- **Hash Identification** - Automatically identify hash types:
  - MD5, SHA-1, SHA-224, SHA-256, SHA-384, SHA-512
  - bcrypt, SHA-512 Crypt, SHA-256 Crypt, MD5 Crypt
  - MySQL (old & new), LDAP SHA-1, LDAP SSHA
  - Salted hashes

- **ROT13/Caesar Cipher** - All 26 rotations displayed instantly

## 🔒 Privacy & Security

- ✅ **100% Client-Side** - No data is sent to any server
- ✅ **No External Dependencies** - Works completely offline after first load
- ✅ **No Tracking** - Your data never leaves your browser
- ✅ **Open Source** - Inspect the code yourself

## 🎯 Use Cases

- **Penetration Testing** - Encode payloads for WAF bypass
- **CTF Challenges** - Quick decode for common encoding schemes
- **Malware Analysis** - Decode obfuscated strings
- **Web Development** - Test encoding/decoding implementations
- **Security Research** - Hash identification and analysis

## 🚀 Usage

Simply open the tool in your browser and:
1. Select the transformation type
2. Choose encoding depth (single/double)
3. Paste your input
4. Click Encode or Decode
5. Copy the result

## 💻 Technical Details

- Pure HTML/CSS/JavaScript
- No frameworks or libraries required
- Mobile responsive design
- Dark theme optimized for long sessions

## 📱 Mobile Friendly

Fully responsive design works seamlessly on:
- Desktop browsers
- Tablets
- Mobile phones

## 📝 License

MIT License - Free to use, modify, and distribute

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 🔗 Connect

If you find this tool useful, please ⭐ star the repository!

---

**Built for security researchers, by a security researcher.**
