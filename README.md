# File Portal

A secure file sharing portal built with Flask that allows users to upload files and generate QR codes for easy access.

## Features

- User Authentication System
  - User registration with email and password
  - Secure login/logout functionality
  - Password hashing for security

- File Management
  - Secure file upload system
  - Automatic QR code generation for each uploaded file
  - File download functionality
  - Original filename preservation
  - Timestamp-based file naming

- User Interface
  - Clean and responsive dashboard
  - Flash messages for user feedback
  - File listing with QR code display
  - Easy-to-use navigation

- Security
  - Login required for file uploads
  - Secure file naming
  - Protected file storage
  - Session management

## Technical Details

- Built with Flask framework
- SQLite database using SQLAlchemy
- QR code generation using qrcode library
- Docker support for easy deployment

## Changelog

### v1.2 (2025-05-12)
- Added file upload progress bar with real-time status
- Enhanced QR code modal with improved animations and UI
- Improved overall UI with better card designs and animations
- Added ESC key support for modal closing
- Enhanced button styles with gradients
- Improved mobile responsiveness
- Added visual feedback for user interactions

### v1.1 (2025-05-12)
- Added file deletion functionality
- Improved QR code display with modal popup
- Enhanced responsive design for all devices
- Improved UI/UX with better visual feedback
- Added confirmation dialog for file deletion
- Fixed mobile layout issues

### v1.0 (2025-05-12)

Initial release with the following features:
- User authentication system implementation
- File upload and download functionality
- QR code generation for file sharing
- Docker containerization
- Basic UI implementation with templates
- Database integration with SQLAlchemy
- Security features implementation
