# Royal Roots — Webflow Export Files

## Files Included

| File | Description |
|------|-------------|
| `styles.css` | Complete CSS with all design tokens, layout, and component styles |
| `script.js` | JavaScript for mobile menu, gallery filter, lightbox, and contact form |
| `index.html` | Home page |
| `services.html` | Services & pricing page |
| `gallery.html` | Filterable photo gallery with lightbox |
| `about.html` | About / owner story page |
| `contact.html` | Booking form + business info |

## Design Tokens

| Token | Value |
|-------|-------|
| **Primary (Pink)** | `hsl(340, 82%, 52%)` → `#E0245E` |
| **Background** | `hsl(0, 0%, 100%)` → `#FFFFFF` |
| **Foreground** | `hsl(340, 10%, 15%)` → `#2B2226` |
| **Accent** | `hsl(340, 60%, 94%)` → `#FBEDF1` |
| **Muted text** | `hsl(340, 10%, 45%)` → `#7A6B70` |
| **Border** | `hsl(340, 20%, 90%)` → `#EDDFDF` |
| **Heading font** | Playfair Display (serif) |
| **Body font** | Lato (sans-serif) |
| **Border radius** | 0.5rem (8px) |

## Webflow Rebuild Tips

1. **Fonts**: Add Playfair Display + Lato via Google Fonts in Webflow project settings
2. **Colors**: Create swatches matching the design tokens above
3. **Header**: Use Webflow's Navbar component; set `position: sticky` and `backdrop-filter: blur(8px)`
4. **Grid layouts**: Use Webflow's Grid or Flexbox with the column counts shown in the CSS
5. **Mobile CTA bar**: Create a fixed-bottom div, hide on tablet+ breakpoints
6. **Forms**: Use Webflow's native Form component for the contact page
7. **Gallery lightbox**: Use Webflow's Lightbox component instead of the custom JS
8. **Images**: Replace all placeholder divs with your actual photos
