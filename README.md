# Portfolio — Alexander

Static project pages. Each folder is deployed to Vercel as its own project (Root Directory = folder name), so every page gets its own link and redeploys automatically on every push to `main`.

| Folder | Project |
| --- | --- |
| `norvy/` | Norvy — folding e-bike (Fold Motion) |
| `shift-26/` | SHIFT / 26 — electronic music festival |
| `curfew/` | 9/31 Curfew — Drop 07 |

## How to update a project

1. Edit the files inside the project's folder.
2. Commit and push to `main`.
3. Vercel rebuilds only the project whose folder changed.

## Adding a new project

1. Create a new folder with an `index.html`.
2. In Vercel: Add New → Project → import this repo → set **Root Directory** to the new folder.
