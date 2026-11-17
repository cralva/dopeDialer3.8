DopeDialer 3.8 — Vercel static deployment

Upload this folder to Vercel or commit index.html to a GitHub repository and import it into Vercel. No build command or framework needed.

Supabase project URL and publishable key are embedded in index.html; NEVER add a service-role or secret key.

Before public launch: verify two-account isolation, signup email confirmation, password recovery, task/lead sync and Google Voice on the Vercel domain.

IMPORTANT: The app uses new per-account localStorage keys. Previously synced v3.7 data will load from Supabase after sign-in. Back up v3.7 JSON before changing versions.

This is a beta deployment build, not a production security audit.
