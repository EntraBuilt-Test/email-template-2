# Nordic Affairs Media — Official Interactive Email Template

A luxury, broadcast-grade interactive HTML email template created for **Nordic Affairs Media** (`nordicaffairsmedia.com`).

---

## 📁 Files in this Directory

| File | Description |
| :--- | :--- |
| **`index.html`** | The production email template with bulletproof table layout, Outlook VML buttons, dark mode styling, and responsive 2-column event showcase. |
| **`preview.html`** | The interactive live testing studio for Desktop, Tablet, and Mobile views with real-time merge tag simulation. |
| **`logo.png`** | Nordic Affairs Media official gold logo with transparent background. |
| **`hero.jpg`** | High-production concert & live broadcasting hero image. |
| **`template-bg.jpg`** | Concert crowd & stage lighting background applied directly inside the email template card. |
| **`README.md`** | Usage, customization guide, and ESP merge tags reference. |

---

## 🌟 Included Design & Interactive Features

1. **Brand Identity**:
   - Deep Nordic Midnight Navy (`#070e1b` / `#0d192b`) paired with metallic Nordic Royal Gold (`#d4af37` / `#e5c158`).
   - Official Nordic Affairs Media logo embedded in the header.
2. **Hero Concert Production Showcase**:
   - High-impact widescreen live production stage image with gold accent framing.
   - High-contrast welcome headline ("Welcome to Nordic Affairs Media").
   - Bulletproof gold CTA button (`Explore Media Portfolio →`) redirecting to `https://nordicaffairsmedia.com/en`.
3. **Major Events Covered Showcase (from official site)**:
   - High-credibility 2-column responsive grid featuring 9 landmark events (all clickable and linking to `https://nordicaffairsmedia.com/en`):
     - *Indian Prime Minister Narendra Modi's visit to Sweden*
     - *Former President of India Pranab Mukherjee's visit to Sweden*
     - *Official engagements involving Ulf Kristersson*
     - *State visits by Frederik X*
     - *Presidential visits from Halla Tómasdóttir*
     - *The prestigious Nobel Prize events* (Golden highlight badge)
     - *Royal celebrations & official events involving Carl XVI Gustaf*
     - *Indo-Nordic Summit 2018*
     - *Stockholm Kulturfestivalen*
4. **Interactive 1-Click Rating & Feedback Block**:
   - 1 to 5 Stars / Emojis (`😡`, `🙁`, `😐`, `😊`, `🤩`) with hover zoom and custom link parameter tracking (`?rating=5&email=*|EMAIL|*`).
5. **Editorial & Production Desks**:
   - Direct contacts for press inquiries and live event broadcast production.

---

## 🌐 How to View in Browser

Copy and paste this URL directly into your browser (Chrome, Edge, Safari):
```text
file:///C:/Users/balam/Downloads/template%202/preview.html
```

---

## 🏷️ ESP Merge Tags

| Platform | First Name Merge Tag | Email Address Tag | Unsubscribe Link |
| :--- | :--- | :--- | :--- |
| **Mailchimp** *(Default)* | `*|FNAME|*` | `*|EMAIL|*` | `*|UNSUB|*` |
| **HubSpot** | `{{ contact.firstname }}` | `{{ contact.email }}` | `{{ unsubscribe_link }}` |
| **Brevo (Sendinblue)** | `{{ contact.FIRSTNAME }}` | `{{ contact.EMAIL }}` | `{{ unsubscribe }}` |
| **Klaviyo** | `{{ first_name }}` | `{{ email }}` | `{% unsubscribe %}` |
