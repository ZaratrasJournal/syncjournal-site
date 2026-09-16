# syncjournal-site — deploy-repo voor syncjournal.nl

Alleen wat live staat: de app (index.html), version.json, privacyverklaring en cache-headers.
Broncode/ontwikkeling leeft elders (lokaal). 

- branch `main`  → syncjournal.nl (productie)
- branch `work`  → work.syncjournal.nl (werkversie — app toont daar zelf een 🚧-badge)

Release = work naar main promoveren (fast-forward merge) + version.json bump.
