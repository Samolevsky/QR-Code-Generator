# Barcode Generator

A professional, browser-based barcode generator that creates high-quality barcodes in multiple formats. Generate barcodes for retail, inventory, books, periodicals, and more with customizable colors, margins, and export options.

## Features

- **12 Barcode Formats**: Support for Code 128, Code 39, Code 11, EAN-13, EAN-8, EAN-14, UPC-A, UPC-E, ISBN, ISSN, ITF-14, and PDF417
- **Customizable Appearance**: Adjust barcode colors, background colors, margins, and font sizes
- **Multiple Export Formats**: Download barcodes as PNG or SVG files
- **Responsive Design**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark/Light Theme**: Toggle between dark and light modes for comfortable viewing
- **Real-time Preview**: See your barcode update instantly as you make changes
- **Drag & Drop Colors**: Intuitive color swapping between barcode and background
- **Accessibility**: Full keyboard navigation and screen reader support

## Getting Started

### Quick Start

1. Open `Barcode Generator 0.1.9.2.html` in any modern web browser
2. Select your desired barcode type from the dropdown menu
3. Enter your data in the input field
4. Click the "Generate" button to create your barcode
5. Customize colors, margins, and font size as needed
6. Export your barcode as PNG or SVG

### No Installation Required

This is a standalone HTML application that runs entirely in your browser. No server, no installation, no dependencies to manage.

## User Guide

### Step 1: Choose Your Barcode Type

Click the **Barcode Type** dropdown and select from 12 different formats:

- **Code 128**: Most versatile format, encodes all ASCII characters
- **Code 39**: Simple format for uppercase letters, numbers, and special characters
- **Code 11 (Codabar)**: Used in libraries, blood banks, and parcel delivery
- **EAN-13**: European standard for retail products (13 digits)
- **EAN-8**: Compact version for small products (8 digits)
- **EAN-14**: For wholesale packaging and case-level tracking (14 digits)
- **UPC-A**: US/Canadian retail standard (12 digits)
- **UPC-E**: Compact UPC for small packages (8 digits)
- **ISBN**: International Standard Book Number for books
- **ISSN**: International Standard Serial Number for periodicals
- **ITF-14**: Interleaved 2 of 5 for carton marking (14 digits)
- **PDF417**: 2D stacked barcode for large data capacity

### Step 2: Enter Your Data

The input field changes based on your selected barcode type:

- **Alphanumeric formats** (Code 128, Code 39, Code 11): Enter any valid text, numbers, or symbols
- **Numeric formats** (EAN, UPC, ISBN, ISSN, ITF-14, EAN-14): Enter only digits
- **PDF417**: Enter any text or data

**Digit Counter**: A real-time counter shows how many characters you've entered and validates the required length for numeric formats.

### Step 3: Generate Your Barcode

Click the **Generate** button to create your barcode. The preview will appear instantly in the right panel.

**Error Handling**: If your input is invalid (wrong length, invalid characters), you'll see a clear error message explaining what needs to be fixed.

### Step 4: Customize Appearance

#### Colors

**Barcode Color** (default: black):
- Click the color swatch to open the color picker
- Or type a hex color code directly (e.g., `#000000`)
- Or click the paste icon to paste a color from your clipboard

**Background Color** (default: white):
- Same options as barcode color
- Ensure high contrast for reliable scanning

**Drag & Drop**: Click and drag one color picker onto the other to swap colors instantly.

#### Margins

Use the **Margin Size** slider or number input to adjust white space around your barcode (0-50 pixels). Adequate margins improve scanning reliability.

#### Font Size

Adjust the **Text Font Size** slider to change the size of the text displayed below the barcode (8-40 pixels).

### Step 5: Export Your Barcode

#### Set Export Width (Optional)

Enter a custom width in pixels (100-2000) in the **Export Image Width** field, or leave blank for automatic sizing.

#### Download Options

**Export as PNG**:
- Click the "Export as PNG" button
- Creates a raster image file
- Best for: Printing, embedding in documents, web use
- File format: `.png`

**Export as SVG**:
- Click the "Export as SVG" button
- Creates a vector image file
- Best for: Scalable graphics, professional printing, design software
- File format: `.svg`

## Barcode Type Details

### Code 128
- **Characters**: All 128 ASCII characters
- **Use Cases**: Shipping labels, inventory tracking, general identification
- **Best For**: Maximum flexibility and data density

### Code 39
- **Characters**: A-Z (uppercase), 0-9, and special characters (-, ., $, /, +, %, *)
- **Use Cases**: Industrial applications, military, automotive
- **Best For**: Simple, reliable encoding

### Code 11 (Codabar)
- **Characters**: Numbers and special characters
- **Use Cases**: Libraries, medical applications, FedEx airbills
- **Best For**: Legacy systems and specialized industries

### EAN-13
- **Characters**: 12 digits (13th is checksum)
- **Use Cases**: Retail products, books, consumer goods
- **Best For**: International retail products

### EAN-8
- **Characters**: 7 digits (8th is checksum)
- **Use Cases**: Small retail items, cosmetics, tobacco
- **Best For**: Products with limited label space

### EAN-14
- **Characters**: 13 digits (14th is checksum)
- **Use Cases**: Wholesale packaging, case-level tracking
- **Best For**: Distribution and logistics

### UPC-A
- **Characters**: 11 digits (12th is checksum)
- **Use Cases**: US/Canadian retail products, grocery items
- **Best For**: North American retail

### UPC-E
- **Characters**: 6 digits (compressed UPC-A)
- **Use Cases**: Small consumer products, cosmetics, candy
- **Best For**: Space-constrained packaging

### ISBN
- **Characters**: 10 or 13 digits
- **Use Cases**: Books, publications, academic materials
- **Best For**: Publishing industry

### ISSN
- **Characters**: 8 digits
- **Use Cases**: Magazines, journals, newspapers, periodicals
- **Best For**: Serial publications

### ITF-14
- **Characters**: 13 digits (14th is checksum)
- **Use Cases**: Carton marking, case-level tracking, shipping
- **Best For**: Supply chain and logistics

### PDF417
- **Characters**: Text, numbers, binary data
- **Use Cases**: Driver's licenses, ID cards, shipping labels, inventory
- **Best For**: High data capacity applications

## Tips for Best Results

1. **High Contrast**: Use dark barcode color on light background for optimal scanning
2. **Appropriate Size**: Ensure barcodes are at least 1 inch wide when printed
3. **Quality Print**: Use 300 DPI or higher resolution for printing
4. **Test Scanning**: Always test printed barcodes with a scanner before mass production
5. **Margin Space**: Include sufficient white space (margins) around barcodes
6. **Avoid Distortion**: Don't stretch or compress barcodes disproportionately
7. **Clean Surface**: Print on smooth, non-reflective surfaces for best results

## Browser Compatibility

This application works in all modern browsers:

- Chrome/Edge (recommended)
- Firefox
- Safari
- Opera

**Minimum Requirements**: Any browser with ES6 JavaScript support and HTML5 Canvas API.

## Keyboard Shortcuts

- **Tab**: Navigate between form fields
- **Enter**: Generate barcode (when focused on input field)
- **Space**: Toggle theme (when focused on theme button)
- **Esc**: Close info modal

## Privacy & Security

- **100% Client-Side**: All processing happens in your browser
- **No Data Collection**: No data is sent to any server
- **No Tracking**: No analytics or tracking scripts
- **Offline Capable**: Works without internet connection (after initial load)


## License

This software is provided under the End User License Agreement (EULA) included in the application. 

For full license terms, click the info button (ⓘ) in the application and expand the EULA section.

## Credits

**Designed by**: [Arseny Samolevsky](https://samolevsky.com/)

**Version**: 0.1.9.2

## Support

For questions, issues, or feature requests, visit [samolevsky.com](https://samolevsky.com/)

---

**Made with ❤️ for developers, designers, and businesses who need reliable barcode generation.**
