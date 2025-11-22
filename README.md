# IRL Security - Landing Page

Professional cybersecurity consulting website with neon-inspired design aesthetic.

## Setup

### Local Development
1. Clone this repository
2. Open `index.html` in a browser
3. No build process required - pure HTML/CSS/JS

### Cloudflare Pages Deployment

#### Option 1: Git Integration (Recommended)
1. Push this repository to GitHub/GitLab
2. In Cloudflare Dashboard:
   - Go to Workers & Pages
   - Create a new Pages project
   - Connect to your Git repository
   - Set build settings:
     - Build command: (leave empty)
     - Build output directory: `/`
3. Deploy

#### Option 2: Direct Upload
1. Zip the entire project
2. In Cloudflare Dashboard:
   - Go to Workers & Pages
   - Create > Upload assets
   - Upload the zip file

### Custom Domains
1. In Cloudflare Pages project settings:
   - Go to Custom domains
   - Add `irl-security.ca` and `irl.expert`
2. Update DNS records as instructed

## Structure

```
irl-security/
├── index.html          # Landing page
├── css/
│   └── style.css       # Adapted APT-ACK neon styling
├── js/
│   └── main.js         # Smooth scrolling & animations
└── README.md           # This file
```

## Features

- **Neon Aesthetic**: Adapted from APT-ACK threat intel platform
- **Responsive Design**: Mobile-first approach
- **Zero Dependencies**: Pure HTML/CSS/JS
- **Fast Loading**: No frameworks, minimal CSS
- **Professional**: Toned down from APT-ACK for business context

## Customization

### Colors
- Primary: `#08f` (Blue neon)
- Background: `#000` (Black)
- Text: `#fff` (White)
- Accent: `#aaa` (Gray)

### Fonts
- Headers: Vibur (Google Fonts)
- Body: System font stack

### Content
- Update contact email in `index.html`
- Modify service descriptions as needed
- Replace placeholder content

## Performance

- No external dependencies except Google Fonts
- CSS: ~5KB gzipped
- JS: ~1KB gzipped
- Total page size: <10KB

## Browser Support

- Chrome/Edge: Latest 2 versions
- Firefox: Latest 2 versions
- Safari: Latest 2 versions

## Next Steps

1. [ ] Add services.html page
2. [ ] Add contact form integration
3. [ ] Add case studies/portfolio
4. [ ] Add blog/resources section
5. [ ] Add calendar booking integration
6. [ ] SEO optimization
7. [ ] Analytics integration

## License

Proprietary - IRL Security Consulting
