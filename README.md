# Lagos-Food-Bank-Initiative-final-poe
# LAGOS FOOD BANK INITIATIVE - WEDE5020 FINAL POE

## Student Information
- **Name:** MANENZHE DAKALO PROSPERITY
- **Student Number:** ST104... (replace with yours)
- **Module:** WEDE5020 - Web Development
- **POE Part:** Part 3 - Adding Functionality and SEO
- **Submission Date:** 2 November 2026

## Project Description
Lagos Food Bank Initiative website is a responsive non-profit website aimed at fighting hunger in Lagos, Nigeria. The website allows visitors to learn about our mission, programs, donate food or money, volunteer, and contact our warehouse in Yaba.

This website addresses food insecurity by providing an online platform for donations, volunteer registration, and awareness. It bridges the gap between food waste (40% of Lagos waste is food) and over 2 million people facing hunger.

## Live Links
- **Live Website (GitHub Pages):** https://yourusername.github.io/LagosFoodBank/
- **GitHub Repository:** https://github.com/yourusername/LagosFoodBank
- **Figma Design (Public):** https://www.figma.com/file/yourfigmafile

> Replace the links above with your actual links before submitting

## Website Structure (5 Pages)
1.  **index.html** - Home: Hero, stats, YouTube impact video, Google Maps warehouse location
2.  **about.html** - About: Mission, vision, history, team image
3.  **programs.html** - Programs: School Feeding, Family Support, video explainer
4.  **get-involved.html** - Get Involved: Donation and volunteer form with JavaScript validation
5.  **contact.html** - Contact: Contact form + warehouse address + embedded Google Maps

## Technologies Used (Infrastructure)
- **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
- **Styling:** External CSS (css/style.css) + Internal CSS in each HTML for colour visibility
- **Version Control:** Git & GitHub
- **Design:** Figma for wireframes (Desktop, Tablet, Mobile)
- **External Services:** Google Maps Embed API, YouTube Embed API

## Colour Palette Explanation
| Colour | Hex Code | Meaning | Usage |
| :--- | :--- | :--- | :--- |
| **Primary Green** | `#0a7a3e` | Growth, hope, agriculture, sustainability | Headings, navbar active state, primary buttons, hero background |
| **Accent Yellow** | `#ffba08` | Optimism, energy, nourishment, happiness | Logo accent, CTA buttons, highlights |
| **Dark Grey** | `#1d1d1f` | Strength, stability, trust | Body text, footer background |
| **Light Grey** | `#f8f9fa` | Cleanliness, transparency | Page background |

The combination of green and yellow reflects the Nigerian flag and agricultural identity while communicating hope and food security.

## Logo Explanation
The logo "LAGOS FOOD BANK" uses bold sans-serif font. LAGOS in green (#0a7a3e) represents location and growth, FOOD BANK in yellow accent shows nourishment. The logo is text-based for accessibility and fast loading.

## SEO Implementation (POE Part 3 Requirement)

### 1. Keyword Optimisation
Each page has unique title tags with location keywords:
- Home: "Lagos Food Bank Initiative | Zero Hunger Lagos | Food Donation Nigeria"
- About: "About Us - Lagos Food Bank Initiative | Our Mission"
- Programs: "Our Programs - School Feeding, Family Support | Lagos Food Bank"
- Get Involved: "Get Involved - Donate or Volunteer | Lagos Food Bank"
- Contact: "Contact Us - Warehouse Location Yaba | Lagos Food Bank"

### 2. Meta Tags
- `<meta name="description">` on all pages with 150-160 characters
- `<meta name="keywords">` with relevant terms: Lagos Food Bank, food donation Lagos, zero hunger Nigeria, volunteer Lagos
- `<meta name="author">` and `<meta name="viewport">` for responsiveness

### 3. Alt Text for Images and Iframes
All images and iframes include descriptive alt text for accessibility and SEO:
- `alt="Lagos Food Bank volunteers distributing food to children in community"`
- `alt="Children receiving nutritious school meals from Lagos Food Bank program"`
- `title="Google Maps location of Lagos Food Bank warehouse Yaba Lagos Nigeria"`
- `alt="YouTube video showing Lagos Food Bank food distribution"`

## JavaScript Functionality (POE Part 3 Requirement)

### File: `js/script.js`
1.  **Fade-in Animations:** IntersectionObserver animates cards and hero on scroll using CSS class `.fade-in`
2.  **Interactive Donate Button:** On click, changes text to "Redirecting..." and navigates to get-involved.html
3.  **Client-Side Form Validation (get-involved.html):**
    - Name: Minimum 3 characters, required
    - Email: Must contain "@", required
    - Phone: Must be 11 digits, numeric only
    - Displays inline error messages in red `.error` spans
    - Shows success message "Thank you! Form submitted successfully." and resets form
4.  **Contact Form Validation (contact.html):**
    - Validates name length and displays success message
    - Prevents default form submission for demonstration

## Functional Forms (POE Part 3 Requirement)
- **Donation Form (`get-involved.html`):** Fields: Full Name*, Email*, Phone* (11 digits), Help Type (select), Message. Uses HTML5 `required` and `pattern` attributes + JavaScript validation.
- **Contact Form (`contact.html`):** Fields: Full Name*, Email*, Message*. Uses `required` attribute + JavaScript validation.

Both forms prevent submission if validation fails and show user-friendly error messages.

## Integration of External Services (POE Part 3 Requirement)
1.  **Google Maps Embed:** Embedded in `index.html` and `contact.html` showing warehouse location Plot 15, Olusola Coker Close, Yaba, Lagos. Uses iframe with `loading="lazy"` for performance.
2.  **YouTube Embed:** Embedded in `index.html` (impact video) and `programs.html` (how food banks work explainer) using iframe with `allowfullscreen`.

## Responsive Design
- Desktop: Grid 2 columns, horizontal navbar
- Tablet: Stacked grids, adjusted padding
- Mobile: Single column, vertical navbar, hamburger-ready
- Tested with Chrome DevTools responsive view (768px breakpoint)

## How to Run the Project
1. Download ZIP and extract
2. Open folder in VS Code
3. Right-click `index.html` > Open with Live Server or double-click to open in browser
4. Ensure `css/style.css` and `js/script.js` are linked correctly

## Screenshots
Include in submission PDF or folder `/screenshots`:
1. Desktop Home
2. Mobile Home (375px)
3. Tablet Home (768px)
4. Form validation error
5. Form success message
6. Google Maps embed visible
7. YouTube embed visible

## References (IIE Harvard Style - Adapted)
- Google (2026) *Google Maps Embed API - Yaba, Lagos*. Available at: https://www.google.com/maps (Accessed: 2 November 2026).
- Lagos Food Bank Initiative (2024) *About Us - Lagos Food Bank*. Available at: https://www.lagosfoodbank.org (Accessed: 2 November 2026).
- Mozilla Developer Network (2024) *HTML: HyperText Markup Language - Forms*. Available at: https://developer.mozilla.org/en-US/docs/Web/HTML (Accessed: 2 November 2026).
- Unsplash (2024) *Food donation and volunteer images*. Available at: https://unsplash.com/s/photos/food-donation (Accessed: 2 November 2026).
- W3Schools (2024) *JavaScript Form Validation*. Available at: https://www.w3schools.com/js/js_validation.asp (Accessed: 2 November 2026).
- YouTube (2024) *Food Bank Explainer Video*. Available at: https://www.youtube.com (Accessed: 2 November 2026).

## Declaration
I, MANENZHE DAKALO PROSPERITY, declare that this POE is my own original work except where referenced. All sources have been cited using IIE Harvard referencing.

## End
