# Compose Deploy CI Project

This project is used by [Compose Deploy](https://github.com/totakoko/compose-deploy) to test new commits against Circle CI.

It exposes a server listening on port 8500 returning a specific content.
That content is used in CI to ensure that the deployment is successful.
