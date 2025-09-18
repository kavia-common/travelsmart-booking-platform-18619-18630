# Setup: TravelSmart Booking Platform

## 1) Backend (Express)
Location: travelsmart-booking-platform-18619-18630/express_backend_api

1. Create .env (already scaffolded). Update secrets as needed.
2. Install dependencies:
   npm install
3. Run dev:
   npm run dev
4. Docs:
   http://localhost:3001/docs

## 2) Frontend (Next.js)
Location: travelsmart-booking-platform-18619-18629/nextjs_frontend

1. Create .env (already scaffolded). Update NEXT_PUBLIC_* and secrets as needed.
2. Install dependencies:
   npm install
3. Run dev:
   npm run dev
4. Open:
   http://localhost:3000

## Notes
- Do not commit real secrets; use environment variables in deployment.
- Update NEXT_PUBLIC_API_BASE_URL to point to your backend.
- For Supabase auth redirects set NEXT_PUBLIC_SITE_URL to your deployment URL.
