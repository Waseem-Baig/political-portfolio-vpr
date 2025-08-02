# Vemireddy Prabhakar Reddy - Official Website

A comprehensive political platform for Nellore constituency featuring citizen engagement, grievance management, and community initiatives.

## 🌟 Features

### 🏛️ Core Functionality

- **Citizen Feedback System** - Digital voting and opinion collection
- **Grievance Management** - Comprehensive complaint submission and tracking
- **Mahila Shakti** - Women empowerment platform and registration
- **Youth Engagement** - Yuva Shakti member registration
- **Volunteer Management** - Community volunteer registration system
- **Social Media Warriors** - Digital advocacy platform

### 🎨 User Experience

- **Bilingual Support** - English and Telugu language options
- **Responsive Design** - Works seamlessly on all devices
- **Modern UI/UX** - Clean, professional, and user-friendly interface
- **Real-time Updates** - Dynamic content and form interactions

### 🔧 Technical Features

- **Supabase Integration** - Real-time database and authentication
- **File Upload System** - Support for documents, images, and videos
- **Dynamic Forms** - Location-based dropdowns and conditional fields
- **Progressive Web App** - Fast loading and offline-capable

## 🚀 Quick Start

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for real-time features

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/VemireddyPrabhakarReddy.git
   ```

2. Navigate to the project directory:

   ```bash
   cd VemireddyPrabhakarReddy
   ```

3. Open `index.html` in your web browser or serve via a local server:

   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js
   npx serve .
   ```

4. Visit `http://localhost:8000` in your browser

### Configuration

1. Set up your Supabase project
2. Update `js/supabaseClient.js` with your Supabase credentials:

   ```javascript
   const supabaseUrl = "your-supabase-url";
   const supabaseKey = "your-supabase-anon-key";
   ```

3. Run the database schema from `backend/supabase/schema.sql`

## 📁 Project Structure

```
VemireddyPrabhakarReddy/
├── index.html                 # Homepage
├── css/                       # Stylesheets
│   ├── bootstrap.min.css
│   ├── style.css
│   └── responsive.css
├── js/                        # JavaScript files
│   ├── supabaseClient.js      # Database configuration
│   ├── grievances.js          # Grievance form handling
│   ├── citizen-feedback.js    # Feedback form handling
│   ├── mahila-shakti-grievance.js
│   ├── volunteer.js
│   └── translations.js        # Language translations
├── img/                       # Images and media
├── public/                    # Public assets
├── backend/
│   └── supabase/
│       └── schema.sql         # Database schema
├── grievances.html            # Grievance submission form
├── citizen-feedback.html      # Citizen feedback form
├── mahila-shakti-grievance.html
├── volunteer.html
├── contact.html
├── photogallary.html
└── README.md
```

## 🎯 Key Pages

### 📋 Forms & Engagement

- **Grievances** (`grievances.html`) - Comprehensive grievance submission system
- **Citizen Feedback** (`citizen-feedback.html`) - Digital voting on key issues
- **Mahila Shakti** (`mahila-shakti-grievance.html`) - Women empowerment registration
- **Volunteer Registration** (`volunteer.html`) - Community volunteer signup
- **Youth Engagement** (`yuva-shakthi.html`) - Youth member registration

### 📢 Information Pages

- **Home** (`index.html`) - Welcome and overview
- **Our Initiatives** (`outmotives.html`) - Political objectives and goals
- **Media Gallery** (`photogallary.html`) - Photos and media coverage
- **About** (`blog-single.html`) - Personal and political background
- **Contact** (`contact.html`) - Contact information and office details

## 🗄️ Database Schema

### Core Tables

- `grievances` - Citizen grievance submissions
- `citizen_feedback` - Digital feedback and voting data
- `mahila_shakti_registrations` - Women empowerment platform registrations
- `volunteers` - Volunteer registration data
- `yuva_shakti_members` - Youth engagement registrations

### Features

- **User Authentication** - Optional login system via Supabase Auth
- **File Storage** - Document and media upload capabilities
- **Real-time Updates** - Live data synchronization
- **Data Analytics** - Built-in tracking and reporting

## 🌐 Deployment

### Static Hosting (Recommended)

Deploy to platforms like:

- **Netlify** - Drag and drop deployment
- **Vercel** - Git-based deployment
- **GitHub Pages** - Free hosting for public repositories

### Traditional Hosting

Upload files to any web server supporting:

- HTML5
- CSS3
- Modern JavaScript (ES6+)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature-name`
3. Commit your changes: `git commit -am 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request

## 📞 Support & Contact

### Technical Support

- **Email**: tech-support@vprofficial.com
- **Issues**: Create a GitHub issue for bug reports

### Political Office

- **Address**: Nellore Constituency Office
- **Phone**: [Your phone number]
- **Email**: contact@vprofficial.com

### Social Media

- **Facebook**: [@vemireddyprabhakarreddy](https://www.facebook.com/vemireddyprabhakarreddy)
- **Instagram**: [@vemireddyprabhakarreddy](https://www.instagram.com/vemireddyprabhakarreddy)
- **Twitter**: [@VemireddyVpr](https://x.com/VemireddyVpr)

## 📄 License

Copyright © 2024 Vemireddy Prabhakar Reddy. All Rights Reserved.

This project is proprietary software created for political and public service purposes.

## 🙏 Acknowledgments

- **Citizens of Nellore** - For their trust and support
- **Volunteers and Contributors** - For their dedication to public service
- **Technical Team** - For building and maintaining this platform
- **Telugu Democratic Party (TDP)** - For political support and guidance

---

**Built with ❤️ for the people of Nellore**

_"Serving the community through technology and transparency"_
