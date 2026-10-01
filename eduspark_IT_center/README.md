# EduSpark Coaching Center — Website

A responsive single-page website for an IT coaching institute, built with plain HTML, CSS and vanilla JavaScript. No framework, no npm, no build step.

## Run it

Open `index.html` in any modern browser. That's it.

Icons and fonts load from CDNs (Font Awesome, Google Fonts), so you need an internet connection for them to appear.

## Sections

1. Navbar (sticky, hamburger menu on mobile)
2. Hero with animated terminal card
3. Courses (7 cards with filter chips)
4. Why Learn With EduSpark (6 feature cards)
5. Learning process (4 steps)
6. About with stats
7. Technologies
8. Call to action
9. Contact form
10. Footer

## JavaScript features

- Mobile menu toggle
- Smooth scrolling
- Course filtering; "View Course" pre-selects the course in the contact form
- Form validation (name, email, phone, course) with a success message
- Navbar style change on scroll
- Reveal-on-scroll animations (disabled if the user prefers reduced motion)

## Customize

All edits happen inside `index.html`:

| What | Where |
|---|---|
| Course names, descriptions, skills, durations | `courses` array in the `<script>` |
| Technology badges | `techs` array in the `<script>` |
| Colors | CSS variables in `:root` |
| Phone, email, address | Contact section |
| Social links | Footer (`href="#"` placeholders) |

## Placeholders to replace before going live

- Course durations (currently 3–5 Months)
- Phone number `+91 XXXXX XXXXX`
- Email `info@eduspark.example`
- Social media links

## Notes

- The contact form has no backend. Submitting only shows a success message and sends no data anywhere. To collect enquiries, connect it to a form service or your own API.
- The site makes no claims about placements, student counts, partnerships, reviews or certifications. Keep it that way unless you can back them up.
- Accessibility: keyboard focus styles, labelled form fields, ARIA on the menu button, reduced-motion support.

## Tech

HTML5, CSS3, vanilla JavaScript, Font Awesome 6, Google Fonts (Plus Jakarta Sans, JetBrains Mono).
