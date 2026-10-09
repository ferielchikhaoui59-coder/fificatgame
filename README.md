# Midnight Familiar

A gothic Halloween arcade game: guide a winged black cat through a haunted graveyard.
Everything — graphics, music and sound effects — is generated in the browser, so the
whole game is a single static `index.html` with no build step or dependencies.

## Controls

- Click / tap / Space / ↑ — fly
- P or Esc — pause
- M — mute

## Run locally

Open `index.html` in a browser, or serve the folder:

```bash
npx serve .
```

## Deploy to Vercel

**CLI** (requires Node.js):

```bash
npx vercel --prod
```

When prompted, accept the defaults — framework preset "Other", no build command,
output directory `.`.

**Git import**: push this folder to a GitHub/GitLab/Bitbucket repo, then on
<https://vercel.com/new> import the repo with framework preset **Other** and leave
the build and output settings empty.
