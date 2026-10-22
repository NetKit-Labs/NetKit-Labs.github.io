# NetKit Labs website

Static site for the [NetKit Labs](https://github.com/NetKit-Labs) organization.

- **Website:** https://netkit-labs.github.io/

## Local preview

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Publishing

GitHub Pages publishes the root of the `main` branch. Commit and push changes
there to trigger the Pages build and deployment. The site uses the default
`netkit-labs.github.io` hostname.

Project cards and metadata are in `index.html`, presentation in `styles.css`,
and animation behavior in `main.js`. The canonical URL and social-preview image
use the same public website address above.
