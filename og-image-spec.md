# OG Image Spec — NumberCrunch

Needed for social share previews (Reddit, LinkedIn, Slack, Twitter/X, Product Hunt).
Dimensions: 1200×630px (standard OG)

## Design brief

Dark navy background (#0f172a)

Left side (60% width):
- "NumberCrunch" wordmark (white, bold, ~44px)
- Headline: "Email a spreadsheet. Get back a finished accounting deliverable." (white, bold, 28px, 2 lines)
- Subline: "$149/task · 24-hour turnaround · Bank recs, variance, audit sampling" (amber #f59e0b, 18px)

Right side (40% width):
- Simple icon: envelope → spreadsheet (emoji-style ✉️ → 📊 at large size)
- Or: a clean Excel workpaper mockup (just a table with rows and a green checkmark column)

Bottom bar:
- "numbercrunch.ai" in muted gray (#94a3b8)

## Quick fallback (text-only card)

Dark navy card with:
- Large white text: "Email a spreadsheet. Get back a finished workpaper."
- Amber subtext: "$149/task. Bank recs, variance analysis, expense categorization."
- URL bottom right: numbercrunch.ai

## Product Hunt icon (240×240)

Simple icon: dark navy square with rounded corners, large "NC" in amber (#f59e0b) or a stylized spreadsheet grid icon.

## Where to upload

After deploying to Netlify: place og-image.png in the `landing/` folder.
Netlify will serve it at https://numbercrunch.ai/og-image.png automatically.

## Tools for quick creation (5 min each)
- Canva (free, has OG templates and PH icon templates): canva.com
- Figma (free, 1200×630 frame + 240×240 frame): figma.com
- Remove.bg for any existing logo assets
- Screely.com for screenshot-style previews of the sample workpaper

## Fastest path (< 5 min)
1. Go to canva.com → search "Product Hunt icon" template
2. Navy background, white "NC" or "NumberCrunch" text in amber
3. Download as PNG → upload to PH as your icon
4. Same navy card, 1200×630, for the OG image

## Alt: generate with AI
Use DALL-E / Midjourney prompt:
"minimal flat icon, dark navy blue background (#0f172a), gold/amber (#f59e0b) spreadsheet grid symbol, white text 'NC', rounded corners, Product Hunt app icon style, no gradients"
