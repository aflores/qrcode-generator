# QR Code Generator with Text Overlay

A simple, self-contained HTML application that generates QR codes with customizable text overlay. The application allows you to create QR codes for URLs, phone numbers, and email addresses, with the ability to add a two-line text overlay in the center of the QR code.

## Features

- Generate QR codes for various types of content:
  - URLs
  - Phone numbers
  - Email addresses
  - Email with subject
- Add a two-line text overlay in the center of the QR code
- Automatic text sizing to fit the available space
- Download QR codes as PNG images
- Real-time character count for overlay text
- Format examples with one-click population
- High error correction for better scannability

## Installation

1. Clone or download this repository:
```bash
git clone https://github.com/yourusername/qrcode-generator.git
```

2. No additional dependencies are required! The application uses:
   - QRCode.js (loaded from CDN)
   - Font Awesome (loaded from CDN)

## Usage

1. Open `index.html` in a web browser
2. Enter the content for your QR code:
   - Click the information icon (i) to see format examples
   - Click any example to automatically fill the input
   - Supported formats:
     - URLs: `https://www.example.com`
     - Phone: `tel:+1234567890`
     - Email: `mailto:example@email.com`
     - Email with subject: `mailto:example@email.com?subject=Hello`

3. Enter the overlay text:
   - Maximum 20 characters per line
   - Two lines maximum
   - Text will be automatically sized to fit
   - Text appears in red in the center of the QR code

4. Click "Generate QR Code" to create your QR code

5. Click "Download QR Code" to save the image

## Format Examples

### URLs
```
https://www.example.com
```

### Phone Numbers
```
tel:+1234567890
```

### Email Addresses
```
mailto:example@email.com
```

### Email with Subject
```
mailto:example@email.com?subject=Hello
```

## Technical Details

- The application uses the QRCode.js library for QR code generation
- High error correction level (H) is used to ensure scannability with the text overlay
- The text overlay is automatically sized to fit the available space
- The QR code is generated at 400x400 pixels for optimal quality
- The text overlay area is 35% of the QR code size

## Browser Support

The application works in all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to submit issues and enhancement requests! 