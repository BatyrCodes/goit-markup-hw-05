Web Studio Landing Page
This is a modern, responsive landing page for a digital web studio. It features a clean design with Google Fonts, normalized CSS, and includes sections such as header navigation, a main hero section with a call-to-action button, a footer with social media links, and a modal contact form.

Features
Responsive header with logo and navigation menu

Contact info in the header (email, phone)

Hero section with a strong headline and “Order Service” button that opens a modal

Footer with social media icons and subscription form

Accessible modal popup with contact form including name, phone, email, comment, and privacy acceptance checkbox

SVG icons used via external sprite sheet

Uses normalize.css for cross-browser consistency

Google Fonts: Raleway and Roboto

External CSS and JavaScript file (modal.js) for modal functionality

Modal Component
A stylish and responsive modal window with a smooth backdrop and animation.

Features
Fullscreen semi-transparent backdrop with fade animation

Centered modal with scale and slide effects

Accessible close button with hover and focus styles

Styled inputs and checkboxes with focus feedback

Simple JS toggle for open/close functionality

Usage
Add the CSS styles to your project.

Use HTML markup with data-modal-open, data-modal-close, and data-modal attributes.

Include the JS script to handle modal toggling.


<button data-modal-open>Open Modal</button>

<div class="backdrop" data-modal>
  <div class="modal">
    <button class="btn-close" data-modal-close aria-label="Close modal">×</button>
    <h2 class="modal-title">Modal Title</h2>
    <!-- Your content here -->
  </div>
</div>
