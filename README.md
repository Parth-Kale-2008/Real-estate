# Aura Estates

A premium, luxury real estate consultancy website designed to showcase exclusive properties across India's prime corridors (Mumbai, Delhi NCR, Bengaluru, Hyderabad, and Goa). The platform offers a highly refined, cinematic user experience built with a focus on modern web design principles and fluid interactions.

## Features

- **Cinematic UI/UX:** High-end visual language featuring a subtle noise overlay, custom cursor interactions, and a cinematic skyline vector background.
- **Dynamic Animations:** Custom scroll progress bars, page loader sequences, hero particle animations, and stagger reveal effects on scroll.
- **Responsive Layouts:** Implements modern CSS grid techniques, including a premium "Bento Grid" property showcase, perfectly responsive across mobile, tablet, and desktop views.
- **Market Intelligence Tickers:** Animated statistics tickers and dynamic counter animations to showcase market size and YoY growth.
- **City-Specific Landing Pages:** Dedicated routing for major metropolitan hubs (Mumbai, Delhi NCR, Bengaluru, Hyderabad, and Goa).
- **Interactive Forms:** Beautifully styled, accessible consultation request forms with immediate client-side feedback.

## Tech Stack

The project is built entirely with core web technologies, ensuring maximum performance and full control over the visual presentation without the overhead of heavy frameworks.

- **HTML5:** Semantic document structure.
- **CSS3:** Vanilla CSS featuring custom variables (tokens), modern layouts (Flexbox/Grid), and advanced CSS animations/transitions.
- **Vanilla JavaScript (`abc.js`):** Lightweight custom logic for DOM manipulation, scroll event handling, custom cursor mapping, counter animations, and mobile menu toggling.

## Project Structure

```text
/
├── index.html        # Main landing page featuring properties, market intel, and contact form
├── style.css         # Global stylesheet containing the design system and utility classes
├── abc.js            # Core JavaScript for interactivity and animations
├── mumbai.html       # City-specific property listings (Mumbai)
├── delhi.html        # City-specific property listings (Delhi NCR)
├── bengaluru.html    # City-specific property listings (Bengaluru)
├── hyderabad.html    # City-specific property listings (Hyderabad)
└── goa.html          # City-specific property listings (Goa)
```

## Setup & Running Locally

Since this is a static site built with vanilla technologies, no complex build process is required.

1. Clone or download the repository to your local machine.
2. Navigate to the project directory.
3. Open `index.html` directly in your web browser. 

Alternatively, to avoid any potential CORS issues with local fonts or images, you can serve the directory using a simple local server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if 'serve' is installed)
npx serve .
```
Then visit `http://localhost:8000` or the provided local URL in your browser.
