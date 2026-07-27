# Selected Systems Portfolio

A confidentiality-safe, static portfolio for four client projects delivered in the following domains:

| Domain | Generalized project title | Scope shown publicly |
|---|---|---|
| Retail & hospitality | Restaurant point of sale | High-level operational workflow |
| Hospitality | Hotel point of sale | High-level POS workflow |
| Healthcare retail | Pharmacy operations system | High-level operational workflow |
| Logistics | Parcel transport system | High-level transport workflow |

## Purpose

This repository is a **public capability showcase**, not a client-project source repository. It is designed to be safely published as a GitHub repository and optionally deployed with GitHub Pages.

## Confidentiality policy

This repository deliberately does **not** include:

- Client legal names, logos, or brand assets
- Source code from client engagements
- Screenshots of production systems
- Credentials, API keys, database exports, customer data, or health-related data
- Commercial metrics, contracts, pricing, or non-public technical architecture
- Unverified technology-stack or feature claims

Project names and descriptions are generalized. Add only material you are explicitly authorized to publish.

## Preview locally

Open `index.html` in a browser, or run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish to GitHub

Create an empty public GitHub repository, for example `selected-systems-portfolio`, then from this directory run:

```bash
git init
git add .
git commit -m "Add anonymized systems portfolio"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/selected-systems-portfolio.git
git push -u origin main
```

Do **not** paste a GitHub personal access token into source files, commits, or chat. Authenticate with GitHub Desktop, GitHub CLI, or Git credential manager instead.

### Deploy with GitHub Pages

On GitHub, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub will provide the public URL.

## Before publishing checklist

- [ ] Confirm client contracts permit a public, generalized portfolio entry.
- [ ] Replace only the text you have permission to disclose.
- [ ] Keep all client source code in private repositories unless written permission says otherwise.
- [ ] Scan for secrets before every push (e.g., `git grep -nEi 'password|token|api[_-]?key|secret'`).
- [ ] Review commit history before making any repository public.

## License

The original HTML and CSS in this showcase may be used under the MIT License. Client work and client materials are not included and are not licensed by this repository.
