# Timothy Tate Jr. — Portfolio

Personal portfolio site for Timothy Tate Jr. — independent developer and creative director based in New York City.

- **Live:** [timothytate.is-a.dev](https://timothytate.is-a.dev)
- **Stack:** Single-file HTML/CSS/JS. No framework, no build step.
- **Hosting:** GitHub Pages, with `timothytate.is-a.dev` via [is-a.dev](https://www.is-a.dev/) free subdomain registry.

## Structure

```
.
├── index.html              # general portfolio (public)
├── intivio/
│   └── index.html          # Intivio-tailored pitch (unlisted)
├── CNAME                   # GitHub Pages custom domain
└── .nojekyll               # disables Jekyll processing on Pages
```

## JARVIS demo

The portfolio embeds a live HTML/CSS recreation of **JARVIS // CTRL** — a six-mode AI workstation OS prototype (Core, Agents, Cockpit, Systems, Studio, Comms). Rebuilt in vanilla JS from a Claude Design handoff.

## Local preview

```
py -m http.server 5173
```

Then open [http://localhost:5173](http://localhost:5173).
