# Drape Studio

A saree virtual try-on web app. Upload a photo of a person and a photo of a saree to generate a draped result.

Inspired by the saree virtual try-on pipeline Meesho described in a Google Cloud blog post.

## Features

- Manual 2D and 3D draping modes
- AI auto-fit backend

## Decisions

- Using the free Hugging Face **IDM-VTON** space as the try-on provider, chosen over paid FASHN and paid Replicate
- Ruled out the WeShopAI space because it blocks API access

## Status

In development.
