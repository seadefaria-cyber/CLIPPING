# BFPA (Body-Focused Process Addiction)

Social media content for mom's company.
Instagram: @bodyfocusedprocessaddiction
Platforms: Instagram + TikTok (same content, double upload)

## Schedule
- Monday: Carousel (question or validation post)
- Tuesday: Carousel (neuroscience or reframe post)
- Friday: Video reel (mom talks to camera, 45-75 sec)

## Brand
- Primary: Deep purple (#2D0050)
- Text: White (#FFFFFF)
- Accent: Light purple (#BEA6DC)
- Font: Helvetica Neue Bold, centered

## Rules
- No em dashes
- No emojis on slides
- No @ handles or branding on slides
- Hooks use accessible language (skin picking, hair pulling) not clinical terms
- Clinical terms ok in captions and hashtags
- Captions: one sentence + hashtags
- Watermark photo or AI image on first slide only, faded behind purple
- Video: give concept/hook options, NOT full scripts. Mom speaks naturally.
- Tone: genuine, direct, not corporate, not AI-sounding

## Content Pillars
1. Question posts (drive comments)
2. Validation posts (reduce shame)
3. Neuroscience/conditioning posts
4. Language/reframe posts
5. Clinical specificity posts

## Workflow
1. Generate content in Claude
2. Build preview.html, deploy to Vercel
3. Text mom the link for approval
4. Generate slides with Pillow (1080x1350, 4:5 ratio)
5. Post Mon/Tues/Fri to IG + TikTok

## Tech
- Slide gen: Python Pillow, Helvetica Neue Bold (index=1 in .ttc)
- Image gen: DALL-E 3 via OpenAI API
- Deploy: `vercel --yes --prod` from week folder
- Local files: /Users/seandefaria/sean/bfpa/
