# ApexTopology

Static Nokia SR OS configuration template generator for Containerlab.

## Files

- `index.html` - standalone app artifact.
- `nokia-sr-sim-hardware-db.json` - extracted Appendix A hardware database from Nokia SR-SIM 25.10.R1 documentation.
- `vercel.json` - Vercel static deployment configuration.
- `package.json` - project metadata and helper scripts.

## Local Preview

```bash
npm run start
```

Then open `http://localhost:3000`.

## Deploy To Vercel

Import this folder as a GitHub repository in Vercel. No build command is required; Vercel can serve `index.html` as a static site.

## Source

Hardware options were extracted from Appendix A of Nokia's SR-SIM Installation, Setup, and Deployment Guide 25.10.R1:

https://documentation.nokia.com/sr/25-10/7750-sr/pdf/SR-SIM_Installation_and_Setup_Guide_25.10.R1.pdf
