# VDS4E Device Package Registry

Central package index, catalog metadata, and automated verification pipeline for VDS4E virtual devices.

## 📦 Official GHCR Artifacts

All verified device models are distributed via GitHub Container Registry (OCI Artifacts) under:
`ghcr.io/vds4e/vds4e-<package-id>:<version>`

### Installing Packages

```bash
vds-cli package install ghcr.io/vds4e/vds4e-<package-id>:<version>
```

### Searching Packages

```bash
vds-cli package list vds4e
```

## 📋 Catalog Index

The official index is located in [`catalog.json`](./catalog.json).
