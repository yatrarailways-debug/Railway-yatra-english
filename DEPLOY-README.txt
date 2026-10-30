RAILWAY YATRA — ENGLISH RELEASE

Upload this extracted folder as a NEW site/project. Do not overwrite or delete the existing Netlify site.

Included:
- English-language responsive Railway Yatra home page
- Train directory search (Supabase-backed)
- Station directory search
- Route and scheduled timetable view
- Device-local favourites and CSV export
- Light/dark theme
- PWA install support and offline app-shell cache
- English admin interface

Deployment:
1. Extract the ZIP.
2. Create a NEW Netlify site (or another hosting project) and deploy the extracted folder contents.
3. Test the new URL before changing any Android/TWA configuration.
4. Keep the existing Netlify URL active until the new site is fully verified.

Data safety:
- config.js keeps the existing Supabase project URL and publishable key.
- No SQL scripts are included or run. No database migration or deletion is performed by this package.
- Keep Supabase RLS policies enabled and appropriate.
- Never put a service_role/secret key in browser config.js.

Limitations:
- Timetable/search data comes from the existing Supabase tables and is only as complete as those records.
- No live running status, PNR status, real-time seat availability or fare API is included.
- Offline caching covers the app shell; Supabase searches require internet.
