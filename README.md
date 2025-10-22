# Profile Card — Stage 0 (Frontend Wizards, HNG 13)

A responsive **Profile Card Component** built as part of the **HNG 13 Frontend Wizards Stage 0** task.  
This project demonstrates the use of semantic HTML, CSS styling, and vanilla JavaScript for dynamic content updates.

---

## 🌐 Live Demo
👉 [View Live Project](https://justinaenayio-idu.github.io/profile-card-stage0/)

---

## 💻 GitHub Repository
👉 [GitHub Repo Link](https://github.com/justinaenayio-idu/profile-card-stage0)



## 🌟 Features
- Responsive design (mobile and desktop)
- Accessible HTML structure (semantic tags, alt text, ARIA-friendly)
- Dynamic current time display
- Social media links open in new tabs
- Styled with pure CSS (no frameworks)



## 🧠 Author
**Onyene Justina Enayi**  
- 🌐 [LinkedIn](https://www.linkedin.com/in/justina-onyene/)  
- 🐦 [Twitter](https://x.com/OnyeneEnayi)  
- 💻 [GitHub](https://github.com/justinaenayio-idu)


## 🧪 Testing
See [TESTING.md](./TESTING.md) file for detailed notes on how this project was tested for:

- Functionality (dynamic time, data attributes)

- Responsiveness across screen sizes

- Accessibility compliance

- Browser compatibility


# Stage 1 - Multi-page Application

**HNG 13 Stage 1 Task** - Building on Stage 0 foundation with Contact Us page form validation and About Me page reflections.

## 🚀 Live Demo stage 1
https://profile-card-stage0and1.netlify.app/


## 💻 GitHub Repository stage 1
https://github.com/justinaenayio-idu/profile-card-stage0and1



### Stage 0 Foundation
- **Profile Card Component** (`Task0.html`)
- Semantic HTML with data-testid attributes
- Responsive design (mobile, tablet, desktop)
- Accessible with keyboard navigation
- Dynamic time display in milliseconds

### Stage 1 Continuation - Multi-page Application
Built directly on the Stage 0 foundation with:
- `AboutMe.html` - About Me page with reflections and goals
- `contactUs.html` - Contact form with full validation
- `Task0.html` - Enhanced Profile Card with navigation (updated from Stage 0)

## 🎯 Stage 1 New Features

### Navigation System
- **Fixed bottom navigation** connecting all three pages
- **Consistent design** across entire application
- **Enhanced accessibility** with proper data-testid attributes
- **Responsive behavior** for all screen sizes

### About Me Page (`AboutMe.html`)
- **Bio** - Personal introduction and background
- **Goals in this program** - Specific learning objectives  
- **Areas of low confidence** - Honest self-assessment
- **Note to future self** - Motivational reflection
- **Extra thoughts** - Program expectations and aspirations

### Contact Page (`contactUs.html`)
- **Real-time form validation** with instant user feedback
- **Email format validation** using comprehensive regex
- **Message length validation** (10+ character requirement)
- **Accessibility-first design** - Labels, ARIA attributes, keyboard navigation
- **Success/error messaging** - Clear communication with users

## ✅ Stage 1 Requirements Met

### Contact Page Validation
- ✅ All fields required with proper validation
- ✅ Email must be valid format (name@example.com)
- ✅ Message must be at least 10 characters
- ✅ Success message shows only after valid submission
- ✅ Error messages tied to inputs with aria-describedby

### Data-testid Attributes
**Contact Page:**
- `test-contact-name`, `test-contact-email`, `test-contact-subject`
- `test-contact-message`, `test-contact-submit`
- `test-contact-error-name`, `test-contact-error-email`, etc.
- `test-contact-success`

**About Me Page:**
- `test-about-page`, `test-about-bio`, `test-about-goals`
- `test-about-confidence`, `test-about-future-note`, `test-about-extra`

**Navigation:**
- `test-main-navigation`, `test-nav-profile`, `test-nav-about`, `test-nav-contact`

**Enhanced Profile Card (from Stage 0):**
- `test-profile-card`, `test-user-name`, `test-user-bio`
- `test-user-time`, `test-user-avatar`, `test-user-social-links`
- `test-user-hobbies`, `test-user-dislikes`

## 🧪 Testing
All elements include data-testid attributes for automated testing. To verify:
1. Open browser developer tools
2. Check elements for `data-testid` attributes
3. Test form validation with invalid/valid inputs
4. Verify navigation works between all pages
5. Confirm responsive behavior across devices

## 🛠 Technologies Used
- **HTML5** - Semantic elements (main, section, article, nav, form)
- **CSS3** - Flexbox, CSS Custom Properties, Media Queries
- **Vanilla JavaScript** - Form validation without frameworks
- **Responsive Design** - Mobile-first approach
- **Accessibility** - WCAG compliant patterns


## 📱 Responsive Design
- Mobile (< 480px) - Optimized vertical layouts

- Tablet (481px - 1024px) - Adaptive designs

- Desktop (> 1024px) - Full feature experience

- Consistent navigation across all breakpoints

