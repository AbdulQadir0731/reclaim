# Reclaim — website

Static site for the Reclaim iOS app, served by GitHub Pages at
<https://abdulqadir0731.github.io/reclaim/>.

| Page | URL | Used for |
| --- | --- | --- |
| Landing | `/reclaim/` | App Store *Marketing URL*, Google OAuth *Application home page* |
| Privacy Policy | `/reclaim/privacy/` | App Store *Privacy Policy URL* (required), in-app link (required by guideline 3.1.2), Google OAuth consent screen (required) |
| Terms of Use | `/reclaim/terms/` | App Store *License Agreement* + end of the app description, in-app link (required by guideline 3.1.2) |
| Support | `/reclaim/support/` | App Store *Support URL* (required) |

No build step, no dependencies. Edit the HTML and push; Pages redeploys in about a minute.
Shared styling lives in `assets/style.css`; the brand colours match `Theme.swift` in the app
(`--accent: #0BA678`, `--accent-deep: #06744C`).

Every path is written absolute with the `/reclaim/` prefix, so renaming the repository means
updating those links.
