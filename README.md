# Web Studio Landing Page

A modern, responsive landing page for a digital web studio. Featuring a clean, minimalistic design with Google Fonts and normalized CSS. The page includes a header with navigation and contact info, a hero section with a call-to-action, a footer with social media links, and an accessible modal contact form.

---

## Features

- **Responsive Header:** Logo, navigation menu, and contact info (email, phone).  
- **Hero Section:** Strong headline with an “Order Service” button that triggers the modal popup.  
- **Footer:** Social media icons and a subscription form.  
- **Accessible Modal Popup:** Contact form with fields for name, phone, email, comment, and a privacy acceptance checkbox.  
- **SVG Icons:** Used via external sprite sheet for optimized performance.  
- **Cross-Browser Consistency:** Powered by `normalize.css`.  
- **Google Fonts:** Raleway and Roboto for elegant typography.  
- **External JS & CSS:** Modal functionality separated in `modal.js` and CSS files.

---

## Modal Component

A stylish and responsive modal window featuring smooth backdrop and animation effects.

### Features

- Fullscreen semi-transparent backdrop with fade animation  
- Centered modal with scale and slide effects  
- Accessible close button with hover and focus styles  
- Styled inputs and checkboxes with focus feedback  
- Simple JavaScript toggle for open/close functionality  

---

## Usage

1. Include the CSS styles in your project.  
2. Use the following HTML markup with the appropriate `data-` attributes:  

```html
<button data-modal-open>Open Modal</button>

<div class="backdrop" data-modal>
  <div class="modal">
    <button class="btn-close" data-modal-close aria-label="Close modal">×</button>
    <h2 class="modal-title">Modal Title</h2>
    <!-- Your content here -->
  </div>
</div>
