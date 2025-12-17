# Skinspect - Skin Cancer Prediction Website

This is a comprehensive web application designed to raise awareness about skin cancer and provide accessible tools for early detection. The website offers educational content about melanoma, an AI-powered skin analysis tool, and a risk assessment feature.

This application is built using **HTML5, CSS3, and Vanilla JavaScript** with a focus on responsive design and user experience.

---

## Website Overview

**Purpose:** To provide free, accessible information and tools for skin cancer awareness and early detection.

**Key Pages:**

| Page | Description |
| :--- | :--- |
| `index.html` | Homepage featuring melanoma statistics, ABCDE guide, and call-to-action sections |
| `check-skin.html` | Skin analysis page with QR code and link to AI prediction tool |
| `risk.html` | Personal risk assessment page with questionnaire |

**Key Features:**

| Feature | Description |
| :--- | :--- |
| **Responsive Navigation** | Mobile-first navbar with hamburger menu for smaller screens |
| **Hero Section** | Engaging hero with clear call-to-action buttons |
| **Statistics Dashboard** | Interactive cards displaying melanoma statistics in Indonesia |
| **ABCDE Guide** | Educational section explaining melanoma warning signs |
| **Image Carousel** | Interactive carousel showcasing skin lesion examples |
| **AI Integration** | Seamless connection to Streamlit-based ML prediction tool |
| **QR Code Access** | Mobile-friendly QR codes for quick access to analysis tools |

---

## Tech Stack

* **HTML5**: Semantic markup for accessibility and SEO
* **CSS3**: Modern styling with Flexbox and Grid layouts
* **Vanilla JavaScript**: No dependencies, lightweight and fast
* **Google Fonts**: Poppins font family for typography
* **Responsive Design**: Mobile-first approach with media queries
* **External Integration**: Streamlit app for AI-based skin analysis

---

## Project Structure

```
skinspect/
│
├── index.html              # Homepage
├── check-skin.html         # Skin analysis page
├── risk.html              # Risk assessment page
├── style.css              # Main stylesheet
├── script.js              # JavaScript functionality
│
└── assets/                # Images and media
    ├── hero.jpg
    ├── doctor.png
    ├── senior.png
    ├── mole1.jpg - mole5.jpg
    ├── qr1.png
    └── qr2.png
```

---

## How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/skinspect.git
   cd skinspect
   ```

2. **Open in browser:**
   
   Simply open `index.html` in your web browser:
   ```bash
   # Using default browser (macOS)
   open index.html
   
   # Using default browser (Windows)
   start index.html
   
   # Using default browser (Linux)
   xdg-open index.html
   ```

3. **Optional: Use a local server (recommended for development):**
   
   Using Python:
   ```bash
   # Python 3
   python -m http.server 8000
   ```
   
   Using Node.js (http-server):
   ```bash
   npx http-server -p 8000
   ```
   
   Then open `http://localhost:8000` in your browser.

---

## Key Features Explained

### 1. Educational Content
The homepage provides crucial information about melanoma, including:
- Statistics about skin cancer in Indonesia
- The ABCDE method for identifying suspicious moles
- Information about early detection and survival rates

### 2. AI-Powered Skin Analysis
Users can upload photos of their skin lesions to receive an instant AI-based assessment. The website seamlessly integrates with an external Streamlit application that hosts the machine learning model.

### 3. Accessibility & UX
- Semantic HTML for screen reader compatibility
- High contrast ratios for readability
- Touch-friendly buttons and interactive elements
- Smooth transitions and hover effects
- Mobile-optimized QR codes for easy access

### 4. Performance Optimization
- Minimal external dependencies
- Optimized image loading
- CSS animations instead of JavaScript for better performance
- Efficient event handling with debouncing for resize events

