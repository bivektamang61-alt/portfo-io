# Darkness to Light Tuition Academy

A modern, responsive website for the Darkness to Light Tuition Academy, featuring personalized tutoring services and free educational resources.

## Features

- **Responsive Design**: Works perfectly on all devices
- **Modern UI**: Dark theme with gradient accents
- **Contact Form**: Email integration for consultation bookings
- **Free Resources Section**: Access to study materials and tutorials
- **Student Success Stories**: Real testimonials from students
- **Interactive Elements**: Smooth animations and hover effects

## Recent Updates

- ✅ Changed contact address to "Birtamode 3"
- ✅ Updated student names to "Shristi" and "Denisha"
- ✅ Replaced "Scholarship Success" and "University Admissions" with "Parents Satisfaction"
- ✅ Added "Student Success Stories" section
- ✅ Added "Free Resources" section with downloadable materials
- ✅ Integrated email functionality for consultation bookings

## Setup Instructions

### 1. EmailJS Configuration

To enable email notifications when someone books a consultation:

1. **Sign up for EmailJS**:
   - Go to [emailjs.com](https://www.emailjs.com/)
   - Create a free account

2. **Create an Email Service**:
   - Go to Email Services in your dashboard
   - Add a new service (Gmail, Outlook, etc.)
   - Connect your email account

3. **Create an Email Template**:
   - Go to Email Templates
   - Create a new template with the following variables:
     - `{{from_name}}` - Customer's name
     - `{{from_email}}` - Customer's email
     - `{{phone}}` - Customer's phone number
     - `{{subject}}` - Selected subject
     - `{{message}}` - Customer's message
     - `{{consultation_date}}` - Date of request
     - `{{consultation_time}}` - Time of request

4. **Update the Website**:
   - Replace `YOUR_USER_ID` in `index.html` with your EmailJS User ID
   - Replace `YOUR_SERVICE_ID` and `YOUR_TEMPLATE_ID` in `script.js` with your actual IDs

### 2. GitHub Deployment

To publish your website online:

1. **Create a GitHub Repository**:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/yourusername/your-repo-name.git
   git branch -M main
   git push -u origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click Settings → Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

4. **Your website will be available at**:
   `https://yourusername.github.io/your-repo-name`

## File Structure

```
Darkness-to-Light-Tuition-Academy/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Customization

### Changing Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #06b6d4;
    /* ... other variables */
}
```

### Adding Content
- **Services**: Edit the services section in `index.html`
- **Resources**: Add new resource cards in the resources section
- **Testimonials**: Update student testimonials in the results section

### Contact Information
Update contact details in the contact section:
- Phone: `9709178678`
- Email: `bivektamang@61gmail.com`
- Address: `Birtamode 3`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- Optimized images and assets
- Minified CSS and JavaScript
- Fast loading times
- Mobile-first responsive design

## Support

For technical support or questions about the website, please contact:
- Email: bivektamang@61gmail.com
- Phone: 9709178678

## License

This project is created for Darkness to Light Tuition Academy. All rights reserved.

