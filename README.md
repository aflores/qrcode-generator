# QR Code Generator

A modern, user-friendly web application for generating QR codes with customizable footer text.

## Features

- Generate QR codes from text, URLs, phone numbers, or email addresses
- Add custom footer text below the QR code
- High error correction level for better scanning reliability
- Character limit indicator for footer text
- Format examples for different QR code types
- Download QR codes as PNG images
- Automatic filename generation from footer text
- Local storage for saving and managing QR code entries
- Responsive design with modern UI

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

3. Enter the footer text:
   - Maximum 40 characters
   - Text appears at the bottom of the QR code

4. Click "Generate QR Code" to create your QR code.
   - The QR code will appear with the footer text
   - A download button will appear below

5. Click "Download QR Code" to save the image
   - A PNG file is generated
   - The filename is generated from the footer text

6. Manage saved entries
   - Select from previously saved entries in the dropdown
   - Delete saved entries using the delete button
   - All entries are automatically saved to your browser's local storage

## Technical Details

- Built with vanilla JavaScript
- Uses QRCode.js library for QR code generation
- Font Awesome for icons
- Local storage for saving entries
- Responsive design with CSS Flexbox
- No external dependencies except for QR code generation

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License

## Contributing

Feel free to submit issues and enhancement requests! 
