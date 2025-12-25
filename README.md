# Sirena Tools

**Sirena Tools** is a comprehensive web-based diagnostic suite designed for managing and controlling Sirena robotics products. Built with modern web technologies, it provides a powerful interface for serial communication, log monitoring, and device control through the browser.

## What is Sirena Tools?

Sirena Tools is a high-performance web application that serves as a unified platform for interacting with Sirena's robotics ecosystem. Currently focused on the **LS6 Pro** servo controllers, it enables users to:

- **Serial Log Reading**: Connect to serial devices via the Web Serial API and monitor real-time logs with advanced filtering and search capabilities
- **Servo Control**: Configure and control LS6 servo motors with precise angle and velocity settings
- **Device Diagnostics**: Monitor connection status, baud rates, and device communication in real-time
- **Command Interface**: Send custom commands and interrupts directly to connected devices

The tool eliminates the need for desktop applications by leveraging browser-based technologies, making it accessible across different operating systems and devices.

## Features

- 🔌 **Web Serial API Integration**: Direct browser-based serial communication without additional drivers
- 📊 **Real-time Log Viewer**: High-performance log monitoring with timestamp tracking and message filtering
- 🎛️ **LS6 Servo Controller**: Configure multiple servos (1-16) with individual ID management
- ⚡ **High Baud Rate Support**: Supports baud rates up to 2,000,000 for fast data transfer
- 🎨 **Modern UI**: Clean, responsive interface built with React and Tailwind CSS
- 🔍 **Advanced Filtering**: Filter logs by type (RX, TX, error) and search through log history
- 📝 **Command Bar**: Send custom commands and interrupts to connected devices

## Upcoming Features

We're continuously working to expand Sirena Tools into a comprehensive platform for all Sirena products. Here's what's coming soon:

### 🔗 Share Logs Options
- Export logs to various formats (CSV, JSON, TXT)
- Generate shareable log reports with timestamps and device information
- Cloud-based log storage and sharing capabilities
- Collaborative log analysis features

### 🏫 School Access Options
- Multi-user authentication and role-based access control
- Classroom management features for educators
- Student progress tracking and log history
- Bulk device configuration for educational institutions
- Secure access controls and user management

### 📑 Multiple Tabs & Tools for All Sirena Products
- **Tabbed Interface**: Work with multiple devices simultaneously in separate tabs
- **Product-Specific Tools**: Dedicated interfaces for:
  - LS6 Pro Servo Controllers (current)
  - Additional Sirena robotics products (coming soon)
- **Unified Dashboard**: Centralized view of all connected Sirena devices
- **Cross-Product Integration**: Seamless workflow between different Sirena tools
- **Custom Tool Development**: Framework for adding new product-specific tools

## Getting Started

### Prerequisites

- **Node.js** (v16 or higher recommended)
- A modern web browser with Web Serial API support (Chrome, Edge, Opera)
- A Sirena device (currently LS6 Pro servo controller)

### Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd sirena-tools
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables** (if required):
   Create a `.env.local` file and add any necessary API keys or configuration:
   ```env
   GEMINI_API_KEY=your_api_key_here
   ```

4. **Run the development server**:
   ```bash
   npm run dev
   ```

5. **Open your browser**:
   Navigate to `http://localhost:5173` (or the port shown in your terminal)

### Building for Production

```bash
npm run build
```

The production build will be available in the `dist` directory.

## Usage

1. **Connect Your Device**:
   - Click the "Connect" button in the sidebar
   - Select your serial device from the browser's device picker
   - Configure the baud rate if needed

2. **Monitor Logs**:
   - View incoming serial data in real-time
   - Use filters to show only specific log types
   - Search through log history

3. **Control Servos**:
   - Configure the number of servos and their IDs
   - Set angle and velocity parameters
   - Send commands to control servo movement

4. **Send Commands**:
   - Use the command bar to send custom serial commands
   - Send interrupts (Ctrl+C) when needed

## Development

This project is built with:
- **React 19** - UI framework
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **Tailwind CSS** - Styling

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

[Add your license information here]

## Support

For issues, questions, or feature requests, please open an issue on the repository.

---
