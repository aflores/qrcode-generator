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

1. Enter the text or URL in the first input field
   - Click the info icon for format examples
   - Supported formats: URLs, phone numbers, email addresses

2. Enter footer text (max 40 characters)
   - Character counter shows current length
   - Visual feedback when limit is reached

3. Click "Generate QR Code" to create the QR code
   - The QR code will appear with the footer text
   - A download button will appear below

4. Download the QR code
   - Click the download button to save as PNG
   - Filename is automatically generated from footer text

5. Manage saved entries
   - Select from previously saved entries in the dropdown
   - Delete saved entries using the delete button
   - All entries are automatically saved to local storage

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
