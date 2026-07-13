# kylemason.org

Personal website and portfolio for Kyle Mason (USMC veteran, aviation professional transitioning to network engineering; CCNA and MIS in progress).

Live at **[kylemason.org](https://kylemason.org)**.

## What is here

| File | Purpose |
|---|---|
| `index.html` | Home page |
| `netframe.html` | NetFRAME home-lab case study (7-node Proxmox cluster, VLAN fabric, ZFS/PBS, private GPU LLM platform) |
| `404.html` | Custom not-found page |
| `Kyle-Mason-Resume.pdf` | Resume, linked from the site |
| `robots.txt` | Crawler directives |
| `CNAME` | Custom domain for GitHub Pages (`kylemason.org`) |

## How it is built and deployed

Pure static HTML and CSS, no build step or framework. Edit the `.html` files directly. Deployment is automatic through **GitHub Pages** from the default branch; the `CNAME` file binds the custom domain.

To preview locally, open the files in a browser or serve the directory, for example:

```bash
python3 -m http.server 8000   # then visit http://localhost:8000
```

## License

Released under the [MIT License](LICENSE).
