# Reproduction for problems with `pnpm import`

Looks like `pnpm import` ignores the `preferredVersions` passed to the install function, so it generates the `pnpm-lock.yaml` from scratch.
