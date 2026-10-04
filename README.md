# NOVOS AI — Supabase Connected

Run `supabase-schema.sql` once in Supabase Dashboard → SQL Editor.

GitHub structure:

.github/workflows/novos-ci.yml
.github/workflows/novos-pages.yml
YAMLs/novos-ci.yml
YAMLs/novos-pages.yml
src/supabase.js
supabase-schema.sql
index.html
public/style.css
src/app.js

The `.github/workflows` copies are already included, so GitHub Actions will detect them. The `YAMLs` folder is the reference copy.

The supplied publishable key is used in `src/supabase.js`. Never put a Supabase secret/service-role key or database password in the repo.