ROC Command 3.0 — Single-File Edition

Upload only `index.html` to the root of the public `roc-command-v3` GitHub repository.

Then enable GitHub Pages:
- Source: Deploy from a branch
- Branch: main
- Folder: /(root)

This release uses the existing ROC Command Supabase project and database.
It includes Dashboard, Command, Operations, Clients, Cameras, Digital Library,
Administration, role-aware controls, and company settings in one HTML file.

Security:
- Use only the Supabase Project URL and publishable key.
- Never place a secret or service-role key in this file.
- Authentication users must still be created or invited through Supabase.
