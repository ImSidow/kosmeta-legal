# Kosmeta legal pages

Privacy policy, terms of use and account-deletion page for the Kosmeta app by Appdhis, served by GitHub Pages at <https://imsidow.github.io/kosmeta-legal/>.

| Page | URL | Used by |
|---|---|---|
| `privacy/index.html` | `/privacy/` | the app (sign-in screen, Privacy & face data), Play Console › Privacy policy |
| `terms/index.html` | `/terms/` | the app's sign-in screen |
| `delete-account/index.html` | `/delete-account/` | Play Console › Data safety › account deletion |

Plain HTML with one shared `style.css`; there is no build step. Pushing to `main` republishes the site in about a minute.

When the app's data handling changes (new data sent to a server, a new service provider, a new permission), update `privacy/index.html` and its "Effective" date in the same release, keep it consistent with the Data safety answers in the app repo (`store-listing/android/listing.md`), and ask the owner before pushing, because the pages are public. Contact address for users: support@appdhis.com. Sign-in emails are sent from noreply@appdhis.com.
