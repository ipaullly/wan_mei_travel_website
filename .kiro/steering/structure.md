# Project Structure

## Root Files
- `index.html` - Main landing page with all sections
- `style.css` - Custom CSS styles and responsive design
- `README.md` - Project documentation
- `wan_mei_logo.jpeg` - Company logo file

## Directories
- `images/` - All visual assets including photos, patterns, and icons
  - Service images: `car_hire.jpg`, `safari_tours.jpg`, `hotel_booking.jpg`
  - Background images: `banner.jpg`, `nairobi.jpg`, `kenya_map.jpg`
  - Pattern overlays: `tribe_pattern.jpg`, `offer_pattern.jpg`, `contact_pattern.jpg`
  - Favicon files: `favicon.ico`, `favicon-16x16.png`, `favicon-32x32.png`

## Code Organization
- Single-page application with all content in `index.html`
- Sections organized sequentially: hero, intro, services, offers, location, contact, social, footer
- CSS follows component-based naming (e.g., `.car-container`, `.offer_section`)
- Bootstrap classes mixed with custom CSS classes
- Responsive design using CSS Grid and Flexbox

## Naming Conventions
- CSS classes use snake_case (e.g., `box_shadow_effect`, `footer_style`)
- Image files use descriptive names with underscores
- Section containers follow pattern: `[section]_container` or `[section]-container`