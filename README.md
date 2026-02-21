# SkillWorker Frontend

<div align="center">
  
  ## Modern Web Application
  
  **Professional Service Platform Client Interface**
  
  [![HTML5](https://img.shields.io/badge/HTML5-E34F26.svg?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
  [![CSS3](https://img.shields.io/badge/CSS3-1572B6.svg?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
  [![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E.svg?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
  [![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3-7952B3.svg?logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](../LICENSE)
  
</div>

---

## 📖 Overview

The **SkillWorker Frontend** is a modern, responsive web application that provides an intuitive interface for workers, clients, and administrators to interact with the SkillWorker platform.

### 🎯 Key Features

- **Responsive Design** - Mobile-first, works on all devices
- **Modern UI** - Clean interface with Bootstrap 5
- **Real-time Updates** - Dynamic content loading
- **Interactive Maps** - Sri Lanka district-based service discovery
- **Secure Authentication** - JWT token management
- **Role-Based Views** - Different dashboards for each user type

---

## 💻 Technology Stack

### Core Technologies
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (ES6+)** - Client-side logic
- **jQuery** - DOM manipulation & AJAX
- **Bootstrap 5** - Responsive UI framework

### Libraries & Tools
- **Axios** - HTTP client for API calls
- **SweetAlert2** - Beautiful alert dialogs
- **Font Awesome 6** - Icon library
- **Chart.js** - Data visualization
- **Bootstrap Icons** - Additional icons

### Third-Party Integrations
- **Cloudinary** - Image upload widget
- **PayHere** - Payment gateway
- **Google OAuth** - Social login

---

## 🚀 Quick Start

### Prerequisites
- Web browser (Chrome, Firefox, Edge - latest versions)
- Backend API running on `http://localhost:8080`
- Live Server or HTTP server

### Setup & Run

#### Option 1: VS Code Live Server (Recommended)
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"
4. Application opens at `http://localhost:5500`

#### Option 2: Python HTTP Server
```bash
cd SkillWorker_FrontEnd
python -m http.server 5500
```

#### Option 3: Node.js HTTP Server
```bash
cd SkillWorker_FrontEnd
npx http-server -p 5500
```

Then open: `http://localhost:5500`

---

## 📁 Project Structure

```
SkillWorker_FrontEnd/
├── index.html                           # Landing page
│
├── pages/                               # HTML Pages
│   ├── login-page.html                 # Login interface
│   ├── signup-role-selection.html      # Role selection
│   ├── signup-second-page.html         # Registration form
│   ├── worker-dashboard.html           # Worker dashboard
│   ├── worker-profile.html             # Worker profile view
│   ├── worker-profile-completion.html  # Profile creation
│   ├── worker-profile-preview.html     # Profile preview
│   ├── client-dashboard.html           # Client dashboard
│   ├── admin-dashboard.html            # Admin panel
│   ├── ads-overview.html               # Service listings
│   ├── ad-preview.html                 # Ad detail view
│   └── subscription.html               # Subscription plans
│
├── js/                                  # JavaScript Files
│   ├── main.js                         # Main app logic
│   ├── loginPage.js                    # Login functionality
│   ├── signupRoleSelection.js          # Role selection logic
│   ├── signupSecondPage.js             # Registration logic
│   ├── workerDashboard.js              # Worker dashboard logic
│   ├── workerProfile.js                # Worker profile logic
│   ├── profileCompletion.js            # Profile creation logic
│   ├── workerProfilePreview.js         # Profile preview logic
│   ├── clientDashboard.js              # Client dashboard logic
│   ├── adminDashboard.js               # Admin panel logic
│   ├── adOverview.js                   # Ad listing logic
│   ├── adPreview.js                    # Ad detail logic
│   ├── subscription.js                 # Subscription logic
│   ├── chat.js                         # Chat functionality
│   └── util/                           # Utility Scripts
│       ├── tokenRefreshHandler.js      # JWT refresh logic
│       ├── logoutHandler.js            # Logout functionality
│       ├── mapdata.js                  # Map configuration
│       └── countrymap.js               # District mapping
│
├── css/                                 # Stylesheets
│   ├── style.css                       # Global styles
│   ├── index.css                       # Landing page styles
│   ├── loginPage.css                   # Login page styles
│   ├── signup-role-selection.css       # Role selection styles
│   ├── signup-second-page.css          # Registration styles
│   ├── worker-dashboard.css            # Worker dashboard styles
│   ├── worker-profile.css              # Worker profile styles
│   ├── worker-profile-completion.css   # Profile creation styles
│   ├── worker-profile-preview.css      # Profile preview styles
│   ├── clientDashboard.css             # Client dashboard styles
│   ├── admin-dashboard.css             # Admin panel styles
│   ├── ads-overview.css                # Ad listing styles
│   ├── ad-preview.css                  # Ad detail styles
│   ├── subscription.css                # Subscription styles
│   └── chat.css                        # Chat interface styles
│
└── assets/                              # Static Assets
    ├── icons/                          # App icons
    │   ├── SkillWorker_logo.png
    │   └── workerDefualtPP.png
    └── images/                         # Images
        ├── login.jpg
        ├── loginPage.png
        └── ...
```

---

## 🎨 Pages Overview

### 🔐 Authentication Pages

#### Landing Page (`index.html`)
- Hero section with call-to-action
- Featured services showcase
- How it works section
- Quick navigation to login/signup

#### Login Page (`pages/login-page.html`)
- Email/password authentication
- Google OAuth integration
- Remember me functionality
- Password recovery link

#### Role Selection (`pages/signup-role-selection.html`)
- Choose user type (Worker/Client)
- Visual role cards
- Role descriptions

#### Registration (`pages/signup-second-page.html`)
- Complete signup form
- Email verification
- Password strength validation
- Terms acceptance

---

### 👷‍♂️ Worker Pages

#### Worker Dashboard (`pages/worker-dashboard.html`)
- Profile statistics (views, ratings)
- Service advertisement management
- Subscription status
- Recent activity feed
- Quick actions panel
- Analytics charts

#### Profile Creation (`pages/worker-profile-completion.html`)
- Step-by-step wizard
- Personal information
- Skills and expertise
- Service areas
- Portfolio upload
- Preview before submit

#### Profile Management (`pages/worker-profile.html`)
- Edit profile information
- Update skills
- Manage portfolio
- View profile statistics
- Change subscription

#### Profile Preview (`pages/worker-profile-preview.html`)
- Public-facing profile view
- Portfolio gallery
- Reviews and ratings
- Contact information
- Service advertisements

#### Subscriptions (`pages/subscription.html`)
- Free, Pro, Premium plans
- Feature comparison
- PayHere payment integration
- Subscription history

---

### 👨‍💼 Client Pages

#### Client Dashboard (`pages/client-dashboard.html`)
- Service search with filters
- Category browsing
- Location-based map view
- Top-rated workers showcase
- Recent service ads
- Saved workers list

#### Service Listings (`pages/ads-overview.html`)
- All service advertisements
- Advanced filtering
- Sort by rating, price, location
- Category selection
- Search functionality

#### Ad Preview (`pages/ad-preview.html`)
- Detailed service information
- Worker profile preview
- Reviews and ratings
- Contact/inquiry form
- Related services

---

### 🛡️ Admin Pages

#### Admin Dashboard (`pages/admin-dashboard.html`)
- User statistics and charts
- Recent activity feed
- Content moderation queue
- Platform analytics
- Quick management actions
- System health status

---

## 🔧 Configuration

### API Configuration

Update API base URL in JavaScript files if needed:

```javascript
// Example: js/main.js or specific page JS
const API_BASE_URL = 'http://localhost:8080/api/v1';
```

### Cloudinary Setup

Cloudinary widget configuration (in relevant upload pages):

```javascript
const cloudinaryWidget = cloudinary.createUploadWidget({
  cloudName: 'your_cloud_name',
  uploadPreset: 'your_upload_preset',
  sources: ['local', 'camera'],
  multiple: true,
  maxFiles: 10
}, (error, result) => {
  if (!error && result && result.event === "success") {
    console.log('Upload successful:', result.info);
  }
});
```

---

## 📱 Responsive Design

### Breakpoints
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

### Mobile-First Approach
All pages are built with mobile-first design:
- Flexible grid layouts
- Responsive images
- Touch-friendly buttons
- Collapsible navigation
- Optimized for small screens

---

## 🔐 Security Features

### Authentication
- JWT token storage in `localStorage`
- Automatic token refresh mechanism
- Protected routes (redirect if not authenticated)
- Role-based access control
- Session timeout handling

### Data Validation
- Client-side form validation
- Input sanitization
- Email format validation
- Password strength checking
- File type/size validation

### Example: Protected Page Check
```javascript
// Check if user is authenticated
const token = localStorage.getItem('accessToken');
if (!token) {
  window.location.href = '/pages/login-page.html';
}

// Check user role
const userRole = localStorage.getItem('userRole');
if (userRole !== 'WORKER') {
  window.location.href = '/pages/client-dashboard.html';
}
```

---

## 🎨 Styling Guidelines

### Color Palette
```css
/* Primary Colors */
--primary: #4F46E5;        /* Indigo */
--secondary: #10B981;      /* Green */
--accent: #F59E0B;         /* Amber */
--danger: #EF4444;         /* Red */

/* Neutral Colors */
--gray-50: #F9FAFB;
--gray-100: #F3F4F6;
--gray-800: #1F2937;
--gray-900: #111827;
```

### Typography
```css
/* Font Family */
font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;

/* Font Sizes */
--text-xs: 0.75rem;    /* 12px */
--text-sm: 0.875rem;   /* 14px */
--text-base: 1rem;     /* 16px */
--text-lg: 1.125rem;   /* 18px */
--text-xl: 1.25rem;    /* 20px */
```

### Components
- Cards with subtle shadow
- Rounded corners (8px default)
- Smooth transitions (200ms-300ms)
- Hover effects on interactive elements

---

## 🔄 API Integration Examples

### Login
```javascript
const loginUser = async (email, password) => {
  try {
    const response = await axios.post(`${API_BASE_URL}/auth/login`, {
      email,
      password
    });
    
    // Store tokens
    localStorage.setItem('accessToken', response.data.accessToken);
    localStorage.setItem('refreshToken', response.data.refreshToken);
    localStorage.setItem('userRole', response.data.user.role);
    
    // Redirect based on role
    if (response.data.user.role === 'WORKER') {
      window.location.href = '/pages/worker-dashboard.html';
    } else if (response.data.user.role === 'CLIENT') {
      window.location.href = '/pages/client-dashboard.html';
    }
  } catch (error) {
    console.error('Login failed:', error);
    Swal.fire('Error', 'Invalid credentials', 'error');
  }
};
```

### Fetch Workers
```javascript
const getWorkers = async () => {
  try {
    const response = await axios.get(`${API_BASE_URL}/worker/getall`, {
      headers: {
        'Authorization': `Bearer ${localStorage.getItem('accessToken')}`
      }
    });
    
    displayWorkers(response.data);
  } catch (error) {
    console.error('Error fetching workers:', error);
  }
};
```

### Upload Image
```javascript
const uploadImage = async (file) => {
  const formData = new FormData();
  formData.append('file', file);
  
  try {
    const response = await axios.post(
      `${API_BASE_URL}/upload/image`,
      formData,
      {
        headers: {
          'Authorization': `Bearer ${localStorage.getItem('accessToken')}`,
          'Content-Type': 'multipart/form-data'
        }
      }
    );
    
    return response.data.imageUrl;
  } catch (error) {
    console.error('Upload failed:', error);
  }
};
```

---

## 🐛 Troubleshooting

### Common Issues

#### 1. API Connection Failed
```javascript
// Check if backend is running
// Verify API_BASE_URL is correct
// Check browser console for CORS errors
// Ensure backend CORS allows your origin
```

**Solution:**
- Verify backend is running on `http://localhost:8080`
- Check browser console (F12) for error messages
- Ensure backend CORS configuration includes frontend URL

#### 2. Images Not Loading
```javascript
// Verify Cloudinary configuration
// Check image URLs in console
// Confirm upload permissions
```

**Solution:**
- Check Cloudinary credentials
- Verify upload preset settings
- Check browser network tab for failed requests

#### 3. Login Not Working
```javascript
// Clear localStorage
localStorage.clear();

// Check credentials
// Verify API response
```

**Solution:**
- Clear browser cache and localStorage
- Check network tab for API response
- Verify credentials are correct

#### 4. Blank Page / Nothing Renders
```javascript
// Check browser console for JavaScript errors
// Verify all script files are loaded
// Check HTML syntax
```

**Solution:**
- Open browser DevTools (F12)
- Look for JavaScript errors
- Check network tab for 404 errors

---

## 📝 Development Guidelines

### Adding New Pages

1. **Create HTML file** in `pages/` directory
2. **Create CSS file** in `css/` directory
3. **Create JavaScript file** in `js/` directory
4. **Add navigation links** in existing pages
5. **Test responsiveness** on different screen sizes

### Code Style

- Use meaningful variable names
- Add comments for complex logic
- Follow consistent indentation (2 spaces)
- Use ES6+ features (const, let, arrow functions)
- Modularize code into functions

### Example Code Structure
```javascript
// Constants
const API_URL = 'http://localhost:8080/api/v1';

// DOM Elements
const loginForm = document.getElementById('loginForm');
const emailInput = document.getElementById('email');

// Functions
const handleLogin = async (e) => {
  e.preventDefault();
  // Login logic
};

// Event Listeners
loginForm.addEventListener('submit', handleLogin);
```

---

## 🚢 Deployment

### 🐳 Docker Deployment (Recommended)

The easiest way to deploy the frontend is using our pre-built Docker image.

#### Pull Docker Image

```bash
docker pull lithirajk/skillworker-frontend:v1
```

#### Run with Docker

```bash
# Run frontend container
docker run -d \
  --name skillworker-frontend \
  -p 80:80 \
  lithirajk/skillworker-frontend:v1
```

Access the application at: `http://localhost`

#### Build Docker Image Locally

If you want to build the image yourself:

1. **Create `Dockerfile`** (already included in project):
```dockerfile
FROM nginx:alpine
COPY . /usr/share/nginx/html
EXPOSE 80
CMD ["nginx", "-g", "daemon off;"]
```

2. **Build the image**:
```bash
docker build -t skillworker-frontend:local .
```

3. **Run the container**:
```bash
docker run -d -p 80:80 skillworker-frontend:local
```

#### Docker Compose Integration

For complete setup with backend and database, see the [main Docker documentation](../README.md#-docker-deployment).

---

### 📦 Traditional Deployment

### Build for Production

1. **Minify CSS/JS** (optional but recommended)
```bash
# Use tools like UglifyJS, Terser for JS
# Use CSSNano for CSS
```

2. **Optimize Images**
```bash
# Compress images using tools like TinyPNG
# Use WebP format where possible
```

3. **Update API URLs**
```javascript
// Change to production backend URL
const API_BASE_URL = 'https://api.skillworker.lk/api/v1';
```

### Deployment Options

#### Option 1: Netlify
1. Connect GitHub repository
2. Set build command (if any): Leave empty for static site
3. Set publish directory: `.` (root)
4. Deploy

#### Option 2: Vercel
1. Import project from GitHub
2. Configure project settings
3. Deploy

#### Option 3: AWS S3 + CloudFront
1. Create S3 bucket
2. Enable static website hosting
3. Upload files
4. Configure CloudFront distribution (optional)
5. Set up custom domain

#### Option 4: GitHub Pages
1. Push code to GitHub
2. Go to repository Settings → Pages
3. Select branch (main) and folder (root)
4. Save and access via `username.github.io/repo-name`

---

## 🧪 Testing

### Manual Testing Checklist

- [ ] All pages load correctly
- [ ] Forms submit successfully
- [ ] Validation works
- [ ] Images display properly
- [ ] Navigation works
- [ ] Responsive on mobile/tablet/desktop
- [ ] Authentication flow works
- [ ] API calls succeed
- [ ] Error handling works
- [ ] Loading states display

### Browser Testing

Test on:
- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

---

## 📞 Support

- **Main Documentation**: [../README.md](../README.md)
- **Backend Documentation**: [../SkillWorker_BackEnd/README.md](../SkillWorker_BackEnd/README.md)
- **Issues**: Report bugs on GitHub Issues
- **Questions**: Contact the development team

---

## 🔗 Useful Resources

- [Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.3/)
- [jQuery API](https://api.jquery.com/)
- [Axios Documentation](https://axios-http.com/docs/intro)
- [SweetAlert2 Documentation](https://sweetalert2.github.io/)
- [Font Awesome Icons](https://fontawesome.com/icons)

---

<div align="center">
  
  **Part of the SkillWorker Platform**
  
  [Main Documentation](../README.md) • [Backend](../SkillWorker_BackEnd/README.md)
  
  Built with ❤️ using modern web technologies
  
</div>

