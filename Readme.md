# 🔐 Lua XOR Encryption Tool

<div align="center">
  <img src="https://img.shields.io/badge/Lua-2C2D72?style=for-the-badge&logo=lua&logoColor=white"/>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white"/>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
  <br>
  <img src="https://img.shields.io/github/license/bidzz7/lua-xor-encrypt?style=flat-square"/>
  <img src="https://img.shields.io/github/stars/bidzz7/lua-xor-encrypt?style=flat-square"/>
  <img src="https://img.shields.io/github/issues/bidzz7/lua-xor-encrypt?style=flat-square"/>
  <img src="https://img.shields.io/github/forks/bidzz7/lua-xor-encrypt?style=flat-square"/>
</div>

<br>

<p align="center">
  <img src="preview.gif" alt="Lua XOR Encrypt Preview" width="600px"/>
</p>

## 🌟 Features

- 🔒 **Strong XOR Encryption**: Secure your Lua scripts with robust XOR encryption
- 🎮 **Multiple Lua Environments Support**:
  - Game Guardian (Lua 5.2)
  - Logitech Macros (Lua 5.1)
  - Standard Lua 5.1/5.2
- 💫 **Modern UI/UX**:
  - Stunning particle effects
  - Cyber-themed design
  - Responsive layout
- 🛡️ **Client-Side Processing**:
  - No server uploads
  - Complete privacy
  - Instant encryption
- 📱 **Cross-Platform**:
  - Desktop
  - Mobile
  - Tablet
- ⚡ **Real-Time Feedback**:
  - Visual notifications
  - Process status updates
  - Error handling

## 🚀 Live Demo

Try it now: [Lua XOR Encrypt Live Demo](https://bidzz7.github.io/lua-xor-encrypt)

## 📥 Installation

```bash
# Clone the repository
git clone https://github.com/bidzz7/lua-xor-encrypt.git

# Navigate to project directory
cd lua-xor-encrypt

# Open in browser
# For Windows
start index.html

# For macOS
open index.html

# For Linux
xdg-open index.html
```

## 💻 Usage

1. **Select Your Lua File**
   ```lua
   -- Support for .lua and .txt files
   -- Example: script.lua, macro.txt
   ```

2. **Enter Encryption Key**
   ```lua
   -- Use a strong encryption key
   -- Example: "MySecretKey123!@#"
   ```

3. **Choose Environment**
   ```lua
   -- Available options:
   -- • Game Guardian (Lua 5.2 load)
   -- • Logitech macros (Lua 5.1 loadstring)
   -- • Common Lua 5.2
   -- • Common Lua 5.1
   ```

4. **Click Encrypt**
   ```lua
   -- Output: encrypted_[original_filename].lua
   ```

## 🔧 Technical Details

### Encryption Process
```lua
-- XOR Encryption Algorithm
local function xorEncrypt(text, key)
    local result = ""
    for i = 1, #text do
        local c = string.byte(text, i)
        local k = string.byte(key, ((i-1) % #key) + 1)
        result = result .. string.char(bit32.bxor(c, k))
    end
    return result
end
```

### Decryption Template
```lua
-- Auto-generated decryption code
local function decode(str, key)
    local result = ""
    for i = 1, #str do
        local c = string.byte(str, i)
        local k = string.byte(key, ((i-1) % #key) + 1)
        result = result .. string.char(bit32.bxor(c, k))
    end
    return result
end
```

## 🛡️ Security Features

- **Base64 Encoding**: Additional layer of obfuscation
- **Client-Side Processing**: No data transmission
- **Custom Key Length**: Flexible encryption strength
- **Environment-Specific Templates**: Optimized for different Lua versions

## 🎨 UI/UX Features

- **Particle System**: Interactive background animations
- **Cyber Lines**: Dynamic scanning effect
- **Custom Notifications**: Elegant status updates
- **Responsive Design**: Adapts to all screen sizes
- **Modern Typography**: Orbitron & Rajdhani fonts
- **Color Scheme**:
  ```css
  :root {
      --primary: #00f7ff;
      --secondary: #0066ff;
      --dark-bg: #020c1b;
      --accent: #64ffda;
  }
  ```

## 📚 Dependencies

- [Particles.js](https://vincentgarreau.com/particles.js/) - Background effects
- [Bulma CSS](https://bulma.io/) - Modern CSS framework
- [Font Awesome](https://fontawesome.com/) - Icons
- [Google Fonts](https://fonts.google.com/) - Typography

## 🔄 Updates

- [x] Initial release with basic encryption
- [x] Added multiple Lua environment support
- [x] Implemented modern UI/UX
- [ ] Add batch processing
- [ ] Implement custom templates
- [ ] Add encryption strength analyzer

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add: AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Contact

Bidzz Official - [@bidzz7](https://t.me/bidzz7)

Channel Link: [Bidzz Official | Channel](https://t.me/cheatbybidzz)

## 🌟 Support

If you find this project useful, please consider giving it a star ⭐️

<div align="center">
  <img src="https://forthebadge.com/images/badges/built-with-love.svg"/>
  <img src="https://forthebadge.com/images/badges/powered-by-coffee.svg"/>
</div>

---
<p align="center">© 2025 Bidzz Official. All rights reserved.</p>

> **Note**: This tool is for educational purposes only. Please respect software licenses and intellectual property rights.