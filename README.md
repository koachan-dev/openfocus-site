# OpenFocus — Marketing & Privacy Site

Static site for [OpenFocus](https://apps.apple.com), a minimal pomodoro timer for iOS.

Deployed via GitHub Pages from this repository's `main` branch.

## Structure

```
.
├── index.html              # English landing
├── privacy/index.html      # English privacy policy
├── ja/
│   ├── index.html          # Japanese landing
│   └── privacy/index.html  # Japanese privacy policy
└── assets/
    └── style.css
```

## Local preview

```bash
python3 -m http.server 8000
# open http://localhost:8000
```
