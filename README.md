# House of Rays Careers

Job application form for House of Rays Medical Co. A static page (`index.html`) hosted on GitHub Pages.

- Applications are stored in a private Supabase database, never in this repo.
- `config.js` holds only the public Supabase address and the public (anon) key. That key can only add applications; it cannot read them.
- Never commit a `service_role` key or any other secret to this repository.
