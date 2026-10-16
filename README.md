# The Discovery Lab Wiki
How to Contribute

## Project Sturcture
Inside of your Astro + Starlight project, you'll see the following folders and files:
.
├── public/
├── src/
│   ├── assets/
│   ├── content/
│   │   ├── docs/
│   │   └── config.ts
│   └── env.d.ts
├── astro.config.mjs
├── package.json
└── tsconfig.json

Starlight looks for .md or .mdx files in the src/content/docs/ directory. Each file is exposed as a route based on its file name.

Images can be added to src/assets/ and embedded in Markdown with a relative link.

Static assets, like favicons, can be placed in the public/ directory.

## Commands
All commands are run from the root of the project, from a terminal:
