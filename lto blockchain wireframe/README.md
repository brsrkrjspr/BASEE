# LTO Blockchain Vehicle Registration System - Wireframes

## Overview
This is a comprehensive wireframe collection for the LTO Blockchain Vehicle Registration System. The wireframes demonstrate the user interface and user experience for different user roles in the system.

## Files Structure

### Public Pages
- `index.html` - Public landing page with service information
- `search.html` - Public document verification page
- `login.html` - User login page
- `register.html` - User registration page

### Dashboard Pages (Role-based)
- `owner-dashboard.html` - Vehicle Owner Dashboard
- `clerk-dashboard.html` - LTO Clerk Dashboard
- `verifier-dashboard.html` - Emission & Insurance Verifier Dashboard
- `admin-dashboard.html` - System Administrator Dashboard

### Functional Pages
- `registration-wizard.html` - Multi-step vehicle registration form
- `document-viewer.html` - Digital OR/CR viewer with blockchain verification
- `settings.html` - User profile and notification settings

### Styles
- `styles.css` - Comprehensive CSS stylesheet for all pages

## Key Features Demonstrated

### Authentication & Authorization
- Role-based login system
- User registration with different account types
- Secure authentication flow

### Dashboard Functionality
- **Owner Dashboard**: Registration, applications tracking, notifications
- **Clerk Dashboard**: Pending queue, search, quick verification
- **Verifier Dashboard**: Assigned tasks, approve/reject functionality
- **Admin Dashboard**: User management, organizations, audit logs, reports

### Core Processes
- **Registration Wizard**: 4-step process with document upload
- **Document Viewer**: IPFS-backed documents with CID verification
- **Public Verification**: Third-party document lookup
- **Audit Trail**: Complete transaction history and timeline

### Technical Features
- Blockchain integration (LTO Network)
- IPFS document storage
- QR code verification
- Digital certificates (OR/CR)
- Real-time status updates

## Design System

### Color Scheme
- Primary: #3498db (Blue)
- Secondary: #2c3e50 (Dark Blue)
- Success: #27ae60 (Green)
- Warning: #f39c12 (Orange)
- Danger: #e74c3c (Red)
- Light Gray: #ecf0f1, #f8f9fa

### Typography
- Primary Font: Segoe UI
- Headings: Various sizes with consistent color hierarchy
- Body Text: 16px base with good line spacing

### Components
- Cards with shadows and rounded corners
- Status badges for different states
- Progress indicators and wizards
- Responsive grid layouts
- Interactive buttons and forms

## Responsive Design
All pages are designed to be mobile-friendly with:
- Flexible grid layouts
- Responsive navigation
- Mobile-optimized forms
- Touch-friendly buttons

## Browser Compatibility
- Modern browsers (Chrome, Firefox, Safari, Edge)
- CSS Grid and Flexbox support
- Mobile browsers

## Getting Started
1. Open `index.html` in your browser to start
2. Navigate through different user roles using the login page
3. Test the registration wizard and document viewer
4. Explore the various dashboard functionalities

## Notes
- This is a wireframe/prototype - not a fully functional application
- JavaScript is minimal and used only for basic interactions
- All forms are for demonstration purposes only
- Images and icons are represented with placeholders
- Real blockchain integration would require backend implementation
