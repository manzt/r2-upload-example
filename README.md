# r2-upload-example

This repo contains a two part [github workflow](./.github/workflows/upload.yml) that:

- Writes some files to a directory
- Uploads the contents to a Cloudflare R2 bucket

It requires the following secrets:

- `AWS_ACCESS_KEY_ID`
- `AWS_SECRET_ACCESS_KEY`
- `R2_BUCKET_NAME`
- `R2_ENDPOINT_URL`

It should be easy to repurpose to automate the preparation and upload of static
assets to R2.
