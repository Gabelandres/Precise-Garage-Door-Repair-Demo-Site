# Precise Garage Door Repair redesign

This folder is a self-contained static deployment build. It uses relative asset
paths and hash-based page routes, so the same files work on GitHub Pages and
Vercel without a build step.

## GitHub Pages

1. Upload the contents of this folder to a repository.
2. In the repository settings, open **Pages**.
3. Choose **Deploy from a branch**, select the branch containing these files,
   and use the repository root as the publishing folder.

## Vercel

1. Import the repository into Vercel.
2. Set this folder as the project root when it is part of a larger repository.
3. Use **Other** as the framework preset and leave the build command empty.

The Google map on the Service Areas page requires an internet connection. All
other site assets are included locally.
