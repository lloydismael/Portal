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

### v1.0 (2025-05-12)

Initial release with the following features:
- User authentication system implementation
- File upload and download functionality
- QR code generation for file sharing
- Docker containerization
- Basic UI implementation with templates
- Database integration with SQLAlchemy
- Security features implementation
