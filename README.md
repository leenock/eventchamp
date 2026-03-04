# Eventchamp

**Eventchamp** is a discovery platform for finding events, nightlife, and great hangout spots.
The platform lists **restaurant events, club nights, live music, promotions, and venues** where people can go for entertainment, dates, or social experiences.

This project uses **Next.js** as the frontend and **WordPress as a headless CMS** to manage venues, events, and other content.

---

## Features

* Event listings (parties, live music, DJ nights, promotions)
* Venue discovery (places to hang out, date spots, nightlife)
* Location-based browsing (cities / counties)
* Headless WordPress CMS for content management
* Fast and modern frontend built with Next.js
* Scalable architecture for future expansion

---

## Tech Stack

Frontend:

* Next.js (App Router)
* React
* Tailwind CSS

Backend / CMS:

* WordPress (Headless)
* WordPress REST API

Deployment:

* Vercel (frontend)
* WordPress hosting provider (CMS)

---

## Getting Started

First, install dependencies:

```bash
npm install
```

Then run the development server:

```bash
npm run dev
```

Open your browser and navigate to:

```
http://localhost:3000
```

The page will automatically update as you save your changes.

---


## Future Features

Planned improvements for Eventchamp:

* Event filtering by county or location
* "Tonight" and "This Weekend" event discovery
* Public holiday event listings
* Live online sessions (X, TikTok, Instagram, Facebook)
* Venue reviews and ratings
* User-submitted events

---

## Deployment

The frontend can be deployed easily on **Vercel**.

Recommended architecture:

```
Frontend (Next.js)
https://eventchamp.com

CMS (WordPress)
https://cms.eventchamp.com

API
https://cms.eventchamp.com/wp-json/wp/v2
```

Deploy to Vercel:

```
vercel
```

For more details see the Next.js deployment guide:
https://nextjs.org/docs/app/building-your-application/deploying

---

## Learn More

* Next.js Documentation → https://nextjs.org/docs
* WordPress REST API → https://developer.wordpress.org/rest-api/

---

## License

MIT License
