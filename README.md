# NetKit Labs website

Static site for the [NetKit Labs](https://github.com/NetKit-Labs) organization.

- **Custom domain:** https://netkitlabs.com/
- **GitHub Pages:** https://netkit-labs.github.io/

## Local preview

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Custom domain (GoDaddy DNS)

Point DNS for `netkitlabs.com` at GitHub Pages:

| Type  | Name | Value                 | TTL  |
|-------|------|-----------------------|------|
| A     | `@`  | `185.199.108.153`     | 600  |
| A     | `@`  | `185.199.109.153`     | 600  |
| A     | `@`  | `185.199.110.153`     | 600  |
| A     | `@`  | `185.199.111.153`     | 600  |
| CNAME | `www`| `netkit-labs.github.io.` | 600 |

Remove any parking / default A or forwarding records that conflict. After DNS propagates, enable **Enforce HTTPS** in the repo Pages settings if it is not already on.
