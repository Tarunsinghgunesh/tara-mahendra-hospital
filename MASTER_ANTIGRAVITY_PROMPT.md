# TARA MAHENDRA HOSPITAL — MASTER ANTIGRAVITY BUILD PROMPT

Build a premium, conversion-focused, production-quality healthcare website for:

Tara Mahendra Hospital And Fracture Clinic
तारा महेंद्र हॉस्पिटल एंड फ्रैक्चर क्लिनिक
B-Narayan Gate, Circular Road, Housing Board Colony, Jawahar Nagar, Bharatpur, Rajasthan 321001
Phone: 05644-356340
WhatsApp: 7297840083
Availability: Listed as open 24 hours
Google rating: 4.2/5 from 102 reviews

## 1. CORE OBJECTIVE
Create a website that feels like a premium private hospital brand, not a generic template. The primary conversion goals are:
1. Call the hospital
2. Start WhatsApp conversation
3. Book/request an appointment
4. Get directions/location
5. Build trust through doctors, services, reviews, 24/7 availability and visual professionalism

The design must be modern, medically trustworthy, human, spacious and highly polished.

## 2. TECH ARCHITECTURE
Preferred demo architecture:
- One standalone `index.html`
- Semantic HTML5
- CSS inside the file
- Vanilla JavaScript inside the file
- Google Fonts: Poppins
- Font Awesome CDN for icons
- No React/Next/Vite/build dependency for the demo
- No unnecessary libraries
- All interactions work without console errors

Production architecture recommendation:
Frontend:
- Next.js/React or equivalent component architecture
- TypeScript
- Tailwind/CSS modules
- Reusable sections/components
- Image optimization
- SEO metadata
- Schema.org JSON-LD

Backend:
- API layer/serverless functions
- Appointment endpoint
- Admin dashboard
- Secure authentication for staff/admin
- Database for appointment requests
- Audit logs
- Rate limiting
- Server-side validation
- CAPTCHA/anti-spam
- WhatsApp/call CTA remains client-side
- Email/SMS/WhatsApp notification integration only after credentials are configured

Do not expose secrets in frontend code.

## 3. DESIGN SYSTEM
Primary:
#0B6EBD Medical Blue
#073B63 Deep Navy
#18B6C9 Cyan
#EAF6FC Soft Blue
#F7FBFE Background
#FFFFFF White
#183B56 Text
#64748B Muted
#16A34A Success/Emergency accent

Visual language:
- White/very-light blue clinical canvas
- Deep navy sections for contrast
- Cyan used sparingly for highlights
- Soft shadows
- 18–28px card radii
- Thin translucent borders
- Glassmorphism only where it improves hierarchy
- No excessive gradients
- No childish hospital visuals

Typography:
Poppins
400 / 500 / 600 / 700 / 800

## 4. HEADER
Sticky header with:
- Hospital logo/wordmark placeholder
- Home
- About
- Services
- Doctors
- Why Us
- Reviews
- Contact
- Emergency/Call CTA
- Book Appointment CTA

Desktop:
- premium glass effect after scroll
- subtle blur
- active section indicator

Mobile:
- hamburger menu
- large tap targets
- fixed bottom action bar:
  Call | WhatsApp | Appointment

## 5. HERO
Badge:
“24/7 Healthcare • Bharatpur”

Headline:
“Trusted Orthopedic & Fracture Care in Bharatpur”

Supporting copy:
“Compassionate, professional healthcare with a focus on orthopedic and fracture care, emergency support and patient-first recovery.”

Primary CTA:
Book an Appointment

Secondary CTA:
Call Now

Supporting trust line:
“24/7 Hospital Availability”

Hero visual:
- premium hospital/orthopedic healthcare image
- if final image is unavailable, use a polished placeholder
- never use fake doctor portraits
- floating glass information cards
- subtle medical cross motif
- heartbeat line animation
- floating soft orbs
- blue ambient glow
- depth layers/parallax
- optional lightweight 3D scene

## 6. 3D + MOTION DIRECTION
The 3D treatment should feel premium, restrained and medical.

Use:
- layered depth
- perspective transforms
- floating cards
- mouse-follow parallax on desktop
- scroll-linked depth
- animated gradient/orb background
- glass cards with subtle tilt
- animated ECG/heartbeat line
- soft particle field
- icon micro-interactions
- section reveal
- magnetic CTA hover
- animated counters
- hover elevation

Optional WebGL/Three.js:
Use only if performance remains excellent. If using it, create a lightweight abstract medical 3D object or particle field rather than a heavy anatomical model.

Do NOT use:
- spinning hospital buildings
- cartoonish 3D doctors
- distracting infinite animations
- heavy WebGL on mobile
- motion that reduces readability

Respect `prefers-reduced-motion`.

## 7. TRUST STRIP
Four premium metrics:
- 4.2★ Google Rating
- 102 Google Reviews
- 24/7 Hospital Availability
- Bharatpur Local Healthcare

Animate numbers once when entering viewport.

## 8. ABOUT
Heading:
“Healthcare Built Around Your Recovery”

Content should communicate:
- patient-focused care
- orthopedic/fracture care
- emergency support
- professional medical guidance
- convenient Bharatpur location

Feature chips/cards:
Patient First
Orthopedic Focus
24/7 Availability
Convenient Location

## 9. SERVICES
Exactly these three core service cards:

### Orthopedics & Joint Care
“Professional orthopedic care focused on fractures, bones, joints and mobility-related concerns.”

### 24/7 Trauma & Emergency
“Emergency support for urgent trauma and fracture-related situations, with hospital availability around the clock.”

### Obstetrics & Gynecology
“Dedicated women's healthcare services with a compassionate and patient-centered approach.”

Each card:
- large icon
- short description
- hover lift
- cyan glow accent
- subtle icon animation
- optional “Enquire” CTA

Do not add unsupported medical procedures.

## 10. DOCTORS
Show:
Dr. Gurdeep Singh
Dr. Savneet Singh
Dr. Satvinder Singh

Safe role label:
“Medical Professional”

Safe copy:
- “Focused on delivering attentive patient care and professional medical guidance.”
- “Committed to compassionate healthcare and patient-focused treatment.”
- “Dedicated to supporting patients through professional medical care and guidance.”

Strict rule:
Do not invent:
- degrees
- specialties
- years of experience
- registrations
- awards
- affiliations
- fellowships
- publications

If verified information is later supplied, update these cards.

## 11. WHY CHOOSE US
Four premium cards:
1. 24/7 Availability
2. Patient First
3. Orthopedic Focus
4. Convenient Location

Use animated line icons and subtle reveal.

## 12. REVIEWS
Display:
4.2 / 5
102 Google Reviews

Use only supplied review themes/snippets:
- “Best orthopedic hospital, and best treatment, low price, staff behaviour Good”
- “Good work and good operation, doctors behaviour are very good”
- “Very nice hospital very good service I like this”

Do not fabricate reviewer names, dates, verified badges or additional testimonials.

## 13. EMERGENCY CTA
Deep navy full-width section:
“Need Medical Assistance?”

Actions:
Call 05644-356340
WhatsApp 7297840083

Visual:
- subtle pulse/heartbeat animation
- glowing emergency indicator
- no alarmist flashing

## 14. LOCATION
Show exact address:
B-Narayan Gate, Circular Road, Housing Board Colony, Jawahar Nagar, Bharatpur, Rajasthan 321001

Show:
- phone
- WhatsApp
- 24/7 availability
- directions CTA

Use a map embed only when a legitimate map integration is configured. Otherwise use a clean map placeholder and directions action.

## 15. APPOINTMENT FORM
Fields:
- Name
- Phone
- Preferred Date
- Message

Validation:
- required fields
- Indian phone number validation
- accessible labels
- clear errors
- success toast

Demo mode:
Clearly treat it as a demo/request UI. Never claim an appointment is confirmed without backend confirmation.

Production mode:
POST to secure backend endpoint and show confirmation only after server response.

## 16. ANIMATION SYSTEM
Page load:
- logo fade/slide
- hero content stagger
- CTA rise
- hero image scale-in

Scroll:
- reveal sections
- stagger cards
- counters
- progress/heartbeat line

Hover:
- cards translateY(-6 to -10px)
- subtle 3D tilt
- icon scale
- button glow

Navigation:
- smooth scrolling
- active section highlight
- header compression

Mobile:
- reduced motion intensity
- no heavy cursor effects
- no WebGL if device performance is poor

## 17. ACCESSIBILITY
- semantic landmarks
- keyboard navigation
- visible focus states
- ARIA labels
- proper form labels
- alt text
- sufficient contrast
- reduced motion support
- no hover-only critical information

## 18. SEO
Title:
“Tara Mahendra Hospital & Fracture Clinic | Bharatpur”

Meta description:
“24/7 healthcare in Bharatpur with orthopedic and fracture care, emergency support and patient-focused medical services at Tara Mahendra Hospital & Fracture Clinic.”

Include:
- viewport
- theme-color
- Open Graph metadata
- canonical placeholder only if deployment URL is known
- LocalBusiness/MedicalOrganization structured data only for verified facts

## 19. PERFORMANCE
Target:
- fast first paint
- minimal JS
- lazy-loaded below-fold images
- optimized images
- no layout shift
- transform/opacity for animation
- avoid huge videos
- avoid heavy 3D libraries unless needed
- no console errors

## 20. FOOTER
Include:
Tara Mahendra Hospital And Fracture Clinic
“Care • Heal • Restore”

Quick links
Services
Doctors
Reviews
Contact

Contact:
05644-356340
7297840083
Bharatpur, Rajasthan

Subtle developer credit:
“Crafted by TK Web Solutions | Founder: Tarun Singh, Bharatpur”

## 21. FINAL QUALITY BAR
The final site must look like a ₹50,000–₹1,00,000+ premium agency healthcare website.

It must NOT look like:
- a basic AI-generated landing page
- a generic bootstrap template
- an overcrowded hospital portal
- a cartoon website

Before finishing:
- test desktop 1440/1920
- tablet 768/1024
- mobile 320/375/414
- check every CTA
- check navigation
- check form validation
- check accessibility
- check animation smoothness
- check no horizontal overflow
- check no console errors
- check all supplied factual information
