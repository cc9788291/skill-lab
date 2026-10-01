# Skill Lab

A small Node.js practice app with three browser skills: Quick Math, Memory Sequence, and Typing Sprint.

The project is also packaged for npm. The package contains the Node.js server and browser assets.

## Run it

```bash
npm start
```

Open <http://localhost:3000>. For automatic server restarts during edits, use `npm run dev`.

## Publish from GitHub

1. Create an npm automation token and add it to the repository as the `NPM_TOKEN` secret.
2. Push this project to GitHub with the default branch named `main`.
3. Open and merge a pull request into `main`. The workflow publishes the package automatically.

The npm package name is `skill-lab`; npm package names must be unique, so change the `name` field in `package.json` if that name is already taken.
