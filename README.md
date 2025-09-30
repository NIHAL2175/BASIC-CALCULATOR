# Basic Calculator Web Application

A modern, responsive web-based calculator with a clean and intuitive interface. Built with HTML, CSS, and JavaScript.

## Features

### Core Functionality
- **Basic Arithmetic Operations**: Addition (+), Subtraction (−), Multiplication (×), Division (÷)
- **Advanced Operations**: Percentage (%), Square Root (√)
- **Memory Functions**: MC (Memory Clear), MR (Memory Recall), M+ (Memory Add), M- (Memory Subtract)
- **Clear and Delete**: C (Clear all), ⌫ (Delete last digit)

### User Interface
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Clean, gradient-based design with smooth animations
- **Accessibility**: Keyboard support and focus indicators
- **Error Handling**: User-friendly error messages for invalid operations

### Keyboard Support

**Memory Functions:**
- **M**: Memory Add (M+)
- **Ctrl+M**: Memory Clear (MC)
- **Shift+M**: Memory Recall (MR)
- **Alt+M**: Memory Store (MS)
- **Alt+Shift+M**: Memory Subtract (M-)
- **Ctrl+Shift+M**: Memory View (Mv)

**Clear Functions:**
- **Escape**: Clear All (C)
- **E**: Clear Entry (CE)
- **Backspace**: Delete (⌫)

**Basic Operations:**
- **Numbers**: 0-9 keys
- **Decimal**: . key
- **Operators**: +, -, *, / keys
- **Enter or =**: Equals (=)

**Advanced Operations:**
- **%**: Percentage
- **R**: Square Root (²√x)
- **S**: Square (x²)
- **I**: Reciprocal (1/x)
- **N**: Plus/Minus Toggle (+/-)

## File Structure

```
BASIC CALCULATOR/
├── index.html          # Main HTML structure
├── styles.css          # CSS styling and responsive design
├── script.js           # JavaScript calculator logic
└── README.md          # Project documentation
```

## Usage

1. Open `index.html` in any modern web browser
2. Use mouse clicks or keyboard input to perform calculations
3. The calculator supports both basic and advanced operations

### Basic Operations
- Click number buttons or type numbers on keyboard
- Click operator buttons or use keyboard operators (+, -, *, /)
- Press Enter or click = to see the result
- Press Escape or click C to clear

### Memory Functions
- **MC**: Clear memory
- **MR**: Recall value from memory
- **M+**: Add current value to memory
- **M-**: Subtract current value from memory

### Advanced Operations
- **%**: Convert current number to percentage (divide by 100)
- **√**: Calculate square root of current number
- **⌫**: Delete last entered digit

## Technical Details

### Browser Compatibility
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Responsive Breakpoints
- **Desktop**: Full calculator layout
- **Tablet** (≤480px): Adjusted button sizes
- **Mobile** (≤360px): Compact layout

### Error Handling
- Division by zero protection
- Invalid square root (negative numbers)
- Malformed input prevention
- Memory overflow protection

## Design Features

### Visual Design
- Gradient background with glassmorphism effect
- Smooth hover and click animations
- Color-coded buttons for different functions
- Professional typography and spacing

### Accessibility
- Keyboard navigation support
- Focus indicators for screen readers
- High contrast color scheme
- Responsive touch targets

## Customization

The calculator is built with modular CSS and JavaScript, making it easy to customize:

- **Colors**: Modify CSS variables in `styles.css`
- **Layout**: Adjust grid properties in the buttons section
- **Functions**: Add new operations in the JavaScript `handleAction` method
- **Styling**: Update button classes and animations

## Performance

- Lightweight (no external dependencies)
- Fast rendering and calculations
- Optimized for mobile devices
- Minimal memory footprint

## License

This project is open source and available under the MIT License.

---

**Note**: This calculator is designed for educational purposes and can be easily extended with additional mathematical functions or integrated into larger web applications. 