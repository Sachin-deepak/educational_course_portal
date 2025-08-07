# 🎓 Unacademy Course Recommendations

Interactive course recommendation portal for Unacademy featuring UPSC, JEE, NEET, SSC, and CBSE courses. Includes detailed trainer information, comprehensive syllabi, and demo booking functionality with integrated customer support.

## ✨ Features

- **Comprehensive Course Catalog**: Complete information on UPSC, JEE, NEET, SSC, and CBSE courses
- **Detailed Trainer Profiles**: Information about top educators for each course
- **Complete Syllabus Coverage**: Detailed breakdown of topics and subjects
- **Interactive Course Browsing**: Click to explore detailed course information
- **Demo Booking System**: Easy access to course demonstrations
- **Customer Support Integration**: Built-in chatbot for instant assistance
- **Responsive Design**: Works perfectly on all devices and screen sizes
- **Accessibility**: Keyboard navigation and focus management for all users

## 🎨 User Experience Highlights

- **Modern Interface**: Clean, intuitive design for easy course exploration
- **Interactive Elements**: Smooth animations and responsive interactions
- **Professional Presentation**: Elegant display of course information
- **User-Friendly Navigation**: Simple and intuitive course browsing
- **Visual Appeal**: Engaging design that enhances learning experience

## 📚 Available Courses

1. **UPSC Civil Services**
   - Online & Offline (Delhi, Bangalore, Hyderabad)
   - Duration: 12-24 months
   - Top trainers: Roman Saini, Mudit Gupta, Aayush Sanghi, Sudarshan Gurjar

2. **IIT JEE Preparation**
   - Online & Offline (Kota, Hyderabad, Chennai)
   - Duration: 1-2 years
   - Top trainers: Namo Kaul, Mohit Tyagi, Ashwani Tyagi, Ravindra P

3. **NEET UG Medical**
   - Online & Offline (Kota, Pune, Chennai)
   - Duration: 1-2 years
   - Top trainers: Dr. Amit Gupta, Sachin Kapoor, Vivek Singh, Ashish Arora

4. **SSC & Banking Exams**
   - Online Only
   - Duration: 6-12 months
   - Top trainers: Sahil Khandelwal, Rani Singh, Aashish Arora, Naman Shrivastava

5. **CBSE Class 10 & 12**
   - Online Only
   - Duration: 1 Academic Year
   - Top trainers: Sushmita Dey, Ashwini Rathi, Deepika Reddy, Sanjay Mishra

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for chatbot functionality
- No additional software required

### Installation
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start exploring courses immediately

### File Structure
```
Unacademy/
├── index.html          # Main HTML file
├── README.md          # This file
└── .gitignore         # Git ignore file (if using git)
```

## 🎯 How to Use

1. **Browse Courses**: View all available courses on the main page
2. **Click for Details**: Click on any course card to see detailed information
3. **View Information**: Each modal shows:
   - Course title and tags
   - Top trainers
   - Complete syllabus
   - Contact button for demo
4. **Close Modal**: Click the × button, click outside, or press Escape
5. **Chat Support**: Use the integrated Engati chatbot for assistance

## 🛠️ Customization

### Adding New Courses
1. Open `index.html`
2. Find the `courseData` object in the JavaScript section
3. Add a new course object with the required properties:
   ```javascript
   newCourse: {
     title: "Course Title",
     tags: ["Tag1", "Tag2", "Tag3"],
     trainers: ["Trainer1", "Trainer2", "Trainer3"],
     syllabus: ["Topic1", "Topic2", "Topic3"]
   }
   ```
4. Add a new course card in the HTML section
5. Update the onclick handler to call `openModal('newCourse')`

### Changing Colors
- Modify the CSS variables in the `<style>` section
- Update gradient backgrounds in `.body` and `.modal-content`
- Adjust glass effect opacity values

### Updating Chatbot
- Replace the Engati script with your own chatbot integration
- Update the bot key and configuration as needed

## 🌐 Deployment

### GitHub Pages
1. Create a GitHub repository
2. Upload `index.html`
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://username.github.io/repository-name`

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop `index.html`
3. Your site is instantly live!

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Import your GitHub repository
3. Deploy with one click

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🔧 Technical Details

- **Backdrop Filter**: Uses CSS backdrop-filter for glass effects
- **CSS Grid**: Responsive layout using CSS Grid
- **CSS Animations**: Smooth transitions and hover effects
- **JavaScript**: Vanilla JS for modal functionality
- **No Frameworks**: Pure HTML, CSS, and JavaScript

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

- **Website Issues**: Open an issue on GitHub
- **Course Inquiries**: Use the integrated chatbot
- **Technical Support**: Contact the development team

## 🎉 Acknowledgments

- Design inspiration from modern glassmorphism trends
- Engati for chatbot integration
- Unacademy for course content structure

---

**Made with ❤️ for educational excellence**
