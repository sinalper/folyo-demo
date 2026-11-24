# Folyo demo

The password page of the Folyo demo, served with GitHub Pages: https://sinalper.github.io/folyo-demo/

This repository holds only that static page. The password check, the server start and the
sign-in happen in the demo gate (a Supabase Edge Function); no code or secret is kept here.
The page is generated from the main repository with `node deploy/supabase/sb.mjs gate page index.html`.
