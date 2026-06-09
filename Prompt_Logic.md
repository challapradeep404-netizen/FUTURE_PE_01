# 🧩 Prompt Logic – AI Website Copy Generator (Elysian Cafe)

## 1. Objective
To design an AI prompt system that generates professional, engaging, and brand‑aligned website copy for **Elysian Cafe**, a modern premium café located in Hyderabad.  
The goal is to produce homepage and section texts that highlight the café’s unique atmosphere, offerings, and customer experience.

---

## 2. Business Context
- **Business Name:** Elysian Cafe  
- **Location:** Jubilee Hills, Hyderabad  
- **Services:** Organic coffee, fresh pastries, gourmet food, quiet work zone, social spaces  
- **Target Audience:** Young professionals, students, creatives, coffee lovers  
- **Unique Selling Points:** Premium organic coffee, green & serene ambience, work‑friendly spaces, delicious food, free high‑speed WiFi  

---

## 3. Prompt Design Principles
- **Identity Anchoring:** Each prompt begins with “Generate a promotional homepage design for Elysian Cafe…” to ensure brand alignment.  
- **Tone Control:** Prompts specify “modern premium café” and emphasize warmth, elegance, and productivity.  
- **Content Focus:** Prompts direct the AI to generate copy for specific sections (Hero, About, Why Choose Us, Experience, CTA, Footer).  
- **Clarity & Brevity:** Responses must be concise, engaging, and suitable for website copy.  

---

## 4. Structure
- Each section of the homepage is treated as a **separate block** within the prompt.  
- Prompts explicitly mention the section name and required text.  
- Outputs are stored in `outputs/homepage.txt` and visual mockups in `assets/homepage_mockup.png`.  

---

## 5. Balance of Information
- **Informative:** Provide exact details (location, services, facilities).  
- **Persuasive:** Highlight ambience, premium quality, and customer experience.  
- **Supportive:** Ensure tone is welcoming and customer‑oriented.  

---

## 6. Example Prompt Template
**General Template:**
"Generate a promotional homepage design for [Business Name], a modern premium café located in [City]. Include the following sections and text exactly: [Insert Section Details]."

**Worked Example:**
Prompt: "Generate a promotional homepage design for Elysian Cafe, a modern premium café located in Hyderabad.  

Include the following sections and text exactly:

Hero Section  
Headline: 'Where Every Sip Feels Like Home'  
Subheadline: 'Discover Hyderabad’s modern premium café to relax, connect, and create.'  
CTA Button: 'Visit Us Today'

About Elysian Cafe  
Text: 'Welcome to Elysian Cafe, your retreat in the heart of Hyderabad. Enjoy organic coffee, fresh pastries, and a warm, inviting ambiance perfect for social gatherings or focused work. Whether you’re unwinding with friends or getting productive in our quiet zone, every visit is a special experience.'  
CTA Button: 'Learn More'

Why Choose Us  
- Organic Coffee Excellence  
- Green & Serene Ambiance  
- Work-Friendly Spaces  
- Delicious Food Selection  
- Free High-Speed WiFi

Experience Elysian Cafe  
Text: 'Relax in style, savor gourmet bites, or get work done in our dedicated quiet zone. Discover your perfect spot at Elysian Cafe.'

Call-to-Action Section  
Text: 'Your Perfect Café Moment Awaits'  
Subtext: 'Book your table or drop by for a visit. We can’t wait to welcome you!'  
CTA Buttons: 'Book a Table | Contact Us | Visit Us'

Footer  
Call Us: +91 98765 43210  
Visit Us: Jubilee Hills, Hyderabad"
---

## 7. Outcome
This prompt logic ensures that all generated homepage content is:
- Consistent with Elysian Cafe branding.  
- Warm, inviting, and professional.  
- Balanced between factual information and persuasive storytelling.  
- Structured into clear sections that are website‑ready and conversion‑focused.  
