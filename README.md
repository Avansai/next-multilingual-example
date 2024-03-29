# ![next-multilingual](./next-multilingual-banner.svg)

![Vercel](https://therealsujitk-vercel-badge.vercel.app/?app=next-multilingual-example)
[![Netlify Status](https://api.netlify.com/api/v1/badges/daa36264-dcf3-4a84-bfed-63af73e35adb/deploy-status)](https://app.netlify.com/sites/next-multilingual/deploys)

This repository is an example application using [`next-multilingual`](https://github.com/Avansai/next-multilingual).

## How to use? 💻

Simply clone the repository and run the standard Next.js commands (examples using `npm`):

- `npm run dev`
- `npm run build`
- `npm run start`

## How to test? 🧪

- Vercel: https://next-multilingual-example.vercel.app/
- Netlify: https://next-multilingual.netlify.app/

## Contributing 💨

This repository isn't meant to be modified directly as it is a copy of the [`example`](https://github.com/Avansai/next-multilingual/tree/main/example) provided in [`next-multilingual`](https://github.com/Avansai/next-multilingual).

The `example` application is used to test `next-multilingual` features during its development which is why it lives in the same repository.

### Updating this repository

Before updating, this repository, we recommend the following steps:

- run `ncu` on `next-multilingual` to use the latest packages
- publish an npm release on `next-multilingual` with the latest changes/features you want to showcase here

When you are ready to update this repository, you can do the following steps:

- run `npm run synchronize-repo`
- run `ncu` to
  - get the latest `next-multilingual` version (or edit manually another version if needed)
  - updates packages; make sure that the versions used for the other packages are compatible with the selected version of `next-multilingual`
