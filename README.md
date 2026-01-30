# Wedding Website - Kristina & Arben

A beautiful, responsive wedding invitation website inspired by the luxury style of Badrutt's Palace.

## Features

- Elegant scroll reveal animations
- Video sections with image fallbacks
- Interactive RSVP form
- Venue section with Google Maps integration
- WhatsApp floating button for easy contact
- Fully responsive design (mobile, tablet, desktop)
- Albanian language content

## Folder Structure

```
wedding-one/
├── index.html              # Main website file
├── README.md               # This file
└── assets/
    ├── images/             # Place your images here
    │   ├── hero-poster.jpg       # Hero section background
    │   ├── story-poster.jpg      # "Historia Jone" section background
    │   ├── adventure-poster.jpg  # "Aventura" section background
    │   ├── venue.jpg             # Venue photo
    │   ├── ceremony.jpg          # Ceremony image
    │   ├── celebration.jpg       # Celebration image
    │   └── ...                   # Other images
    │
    └── videos/             # Place your videos here
        ├── hero-video.mp4        # Hero section video
        ├── story-video.mp4       # "Historia Jone" video
        └── adventure-video.mp4   # "Aventura" video
```

## How to Add Your Own Media

### Images
1. Replace the Unsplash placeholder URLs in `index.html` with paths to your local images
2. Example: Change `https://images.unsplash.com/...` to `assets/images/your-image.jpg`

### Videos
1. Add your video files to `assets/videos/`
2. The website automatically falls back to poster images if videos don't load
3. Recommended video format: MP4 (H.264 codec)
4. Recommended video size: Under 10MB for fast loading

## Customization

### Update Wedding Details
- Names: Search for "Kristina" and "Arben" in index.html
- Date: Search for "15 Qershor 2025"
- Location: Update venue section and Google Maps embed
- WhatsApp number: Update the phone number in the WhatsApp button href

### Update Google Maps
1. Go to Google Maps
2. Find your venue location
3. Click "Share" > "Embed a map"
4. Copy the iframe code
5. Replace the existing iframe in the venue section

### Colors (CSS Variables)
```css
--cream: #F5F1E8;        /* Background color */
--burgundy: #8b3126;     /* Accent color */
--brown: #5C4033;        /* Text color */
```

## Deployment

This is a static website that can be hosted on:
- GitHub Pages
- Netlify
- Vercel
- Any web hosting service

## License

Personal use only.
