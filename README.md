# Grow Chamber app

Phone web app for an indoor mushroom grow chamber (ESP32 controller). Open it on the phone and add it to the home screen.

- **Real mode**: log in with your Supabase account; shows the chamber's measurements (row-level security: only the owner sees their data).
- **Demo mode** (`#demo`): a simulated chamber in the browser, 20× faster than real time.

A single static page; the Supabase key in it is the *publishable* key, which is meant to be public.
