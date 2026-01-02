```md
# MD → HTML Newsletter Email Prompt (With Banner)

## Role
You are a senior email developer and newsletter editor for Tayo360. You write email-safe HTML that renders well in Gmail and Outlook using table-based layout and inline CSS.

## Objective
Convert the following newsletter/article content into a complete HTML email file that includes:
- a top banner section
- clean typography
- mobile-friendly layout
- clear section spacing
- footer branding

## Inputs
Brand name: Tayo360  
Newsletter title: Surah Al-Mu’minun (23:1–4): How Allah Defines True Success  
Preheader text (short): True success begins with prayer, focus, avoiding distractions, and giving.  
Banner image URL: [PASTE YOUR BANNER IMAGE URL HERE]  
Logo image URL (optional): [PASTE LOGO URL HERE OR LEAVE BLANK]  
CTA button text (optional): Read More  
CTA button URL (optional): [PASTE LINK OR LEAVE BLANK]

Article content to convert (paste below):
[PASTE THE FULL ARTICLE TEXT HERE]

## Requirements (Must Follow)
1. Output a single complete HTML document:
   - include `<!doctype html>`, `<html>`, `<head>`, `<body>`
   - include `<meta charset="utf-8">` and mobile viewport meta
2. Use table-based email structure:
   - outer wrapper 100% width
   - centered container width 600px (max-width 600px)
3. Use inline CSS only (no external CSS)
4. Add a banner at the top:
   - full width of the 600px container
   - include alt text: "Tayo360 Newsletter Banner"
5. Typography:
   - body font: Arial, Helvetica, sans-serif
   - base font size 16px
   - line height 1.6
6. Sections:
   - Title area with newsletter title
   - Short intro paragraph
   - Article content formatted into paragraphs
   - Qur’anic verse lines should be visually distinct (use italics and slightly larger font)
7. Footer:
   - “Tayo360 Islamic Mindset and Motivation”
   - optional unsubscribe placeholder text: “Manage preferences / Unsubscribe”
8. Accessibility:
   - include `alt` attributes for images
   - keep good contrast
9. Output only the final HTML code, nothing else.

## Layout Guidance
- Top: banner image
- Under banner: title + preheader line
- Body: formatted article text
- Optional CTA button near the end if CTA URL is provided
- Bottom: footer branding + unsubscribe placeholder

## Deliverable
Return the final email-ready HTML code that I can save as:
`2026-01-weekly.html`
```
