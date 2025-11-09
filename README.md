# Matrix Build Demo - GitHub Actions

This repository demonstrates a multi-platform matrix build strategy using GitHub Actions with artifact management.

## Overview
This workflow showcases:
- Parallel matrix builds for multiple Node.js versions
- Artifact generation for each matrix variant
- Artifact upload and management
- CI/CD best practices

## Matrix Configuration
The workflow builds for:
- Node.js 14.x
- Node.js 16.x
- Node.js 18.x

## Artifacts
Each build generates a unique artifact with the naming convention: `build-4569e89-v{version}`

## Contact
Email: 21f3002781@ds.study.iitm.ac.in
