# YOUWARE.md

This file provides guidance to YOUWARE Agent (youware.com) when working with code in this repository.

## Project Overview

**NC Telepsychiatric Website** - A modern, professional telepsychiatry service website built for North Carolina patients seeking convenient mental health care with specialized ADHD subscription services.

- **Project Type**: React + TypeScript Modern Web Application
- **Entry Point**: `src/main.tsx` (React application entry)
- **Build System**: Vite 7.0.0 (Fast development and build)
- **Styling System**: Tailwind CSS 3.4.17 (Atomic CSS framework)

## Project Details

**Business Focus**: Telepsychiatry services across North Carolina - Landing page for Pinnacle Behavioral Health and Wellness
**Target Audience**: Patients seeking convenient, professional mental health care from home, especially adults with ADHD
**Primary Contact**: (336) 828-2599
**Main Website**: https://www.pinnaclebhw.com/

**Key Services**: 
- Initial ADHD Assessment with psychological testing ($200)
- Follow-up ADHD appointments ($80 per visit)
- Telepsychiatry consultations via secure video with licensed PMHNP
- Adult ADHD medication management and specialized care
- Mental health treatment for depression, anxiety, ADHD
- Crisis interventions and family consultations

**Service Areas**: Raleigh, Charlotte, Durham, Greensboro, Winston-Salem, Asheville, Wilmington, Cary, Chapel Hill, Greenville, Morrisville, Holly Springs, Knightdale, Garner, Apex, and surrounding North Carolina areas.

## Core Design Principles

### Professional Healthcare Aesthetic
- Clean, trustworthy design with medical blue color scheme
- Professional imagery focused on healthcare and telehealth technology
- HIPAA compliance messaging and security emphasis
- Accessible design following healthcare web standards

### User Experience Focus
- Clear conversion paths directing to main website (pinnaclebhw.com)
- Prominent contact information (336) 828-2599
- Multiple backlinks to main practice website
- SEO-optimized anchor text for North Carolina mental health services
- Mobile-responsive design for accessibility

### Content Strategy
- Evidence-based information about telepsychiatry benefits
- Clear service descriptions and patient eligibility
- Professional credibility indicators
- Privacy and security assurances

## Technical Architecture

### Directory Structure

```
project-root/
├── index.html              # Main HTML template
├── src/                    # Source code directory
    ├── App.tsx            # Main application routing
    ├── main.tsx           # Application entry point
    ├── index.css          # Global styles and Tailwind imports
    └── components/        # React components
        ├── Header.tsx     # Navigation with phone/booking CTAs
        ├── Hero.tsx       # Main hero section with value props
        ├── Services.tsx   # Service offerings and insurance info
        ├── About.tsx      # Benefits and technology details
        ├── Contact.tsx    # Contact form and emergency info
        └── Footer.tsx     # Footer with service areas
```

### Component Architecture

- **Header**: Fixed navigation with backlink to main site and phone number (336) 828-2599
- **Hero**: Value proposition with service highlights and hero image
- **Services**: Comprehensive service grid with insurance information
- **ADHDSubscription**: Monthly subscription plans for adult ADHD care with pricing tiers
- **About**: Benefits of telepsychiatry with statistics and technology details
- **Contact**: Appointment request form with contact information
- **Footer**: Service areas, quick links, and medical disclaimer

## Tech Stack

### Core Framework
- **React**: 18.3.1 - Declarative UI library
- **TypeScript**: 5.8.3 - Type-safe JavaScript superset
- **Vite**: 7.0.0 - Next generation frontend build tool
- **Tailwind CSS**: 3.4.17 - Atomic CSS framework

### UI and Styling
- **Lucide React**: Modern icon library for healthcare/tech icons
- **Responsive Design**: Mobile-first approach with healthcare accessibility
- **Professional Color Palette**: Blue (#1e40af) primary with gray neutrals

## Development Commands

- **Install dependencies**: `npm install`
- **Build project**: `npm run build`

## ⚠️ CRITICAL: Do NOT Modify index.html Entry Point

**WARNING**: This is a Vite + React project. **NEVER** modify this critical line in `index.html`:

```html
<script type="module" src="/src/main.tsx"></script>
```

**Why**: This is the core entry point. Any modification will cause the app to completely stop working.

## Key Features Implemented

### User Conversion Features
- Multiple backlinks to main website (https://www.pinnaclebhw.com/) throughout the site
- Updated phone number displays: (336) 828-2599
- Simple ADHD appointment pricing: $200 initial assessment, $80 follow-ups
- Prominent CTAs directing to main practice website
- Contact form with service selection and insurance fields
- Service highlight sections promoting complete mental health services
- SEO-optimized backlinks with keyword-rich anchor text

### Healthcare Trust Signals
- HIPAA compliance messaging
- Licensed PMHNP (Psychiatric Mental Health Nurse Practitioner) credentials
- Security and privacy emphasis
- Professional medical imagery
- Insurance acceptance information

### Service Information
- Comprehensive telepsychiatry service descriptions
- Patient eligibility criteria
- Technology platform details
- Service area coverage across North Carolina

## Content Guidelines

### Medical Compliance
- All medical disclaimers included
- Emergency contact information prominent
- Professional, evidence-based language
- HIPAA compliance references

### SEO and Accessibility
- Semantic HTML structure
- Alt text for all images
- Proper heading hierarchy
- Mobile-responsive design
- Fast loading with optimized images

## Future Enhancement Opportunities

### Functionality Enhancements
- Online appointment scheduling integration
- Patient portal integration
- Insurance verification system
- Telehealth platform integration

### Content Enhancements
- Patient testimonials and success stories
- Provider profiles and credentials
- Educational resources about mental health
- FAQ section for common questions

### Technical Enhancements
- Google Analytics integration for conversion tracking
- HIPAA-compliant contact form backend
- Live chat integration for patient inquiries
- Appointment reminder system integration

## Important Notes

- **Primary CTA**: Direct users to main website (pinnaclebhw.com) and phone (336) 828-2599
- **Featured Service**: Simple per-appointment ADHD care with comprehensive initial assessment
- **Service Focus**: Specialized adult ADHD treatment with transparent pricing and no subscription commitments
- **Geographic Scope**: North Carolina statewide service
- **Compliance**: Healthcare website with appropriate medical disclaimers and emergency information

## ADHD Care Features

### Pricing Structure
- **Initial ADHD Assessment**: $200 (one-time) - Comprehensive evaluation with psychological testing
- **Follow-up Appointments**: $80 per visit - Ongoing medication management and care

### Key Features
- Pay-per-appointment model with no subscriptions or contracts
- Comprehensive initial assessment with psychological testing ($200)
- Affordable follow-up appointments ($80 per visit)
- Flexible scheduling with evening/weekend appointments
- ADHD specialist PMHNP (Psychiatric Mental Health Nurse Practitioner)
- Direct provider access between visits
- Insurance accepted (BCBS NC, Aetna, United, Cigna, Medicare)