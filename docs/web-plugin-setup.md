Web plugin setup

This document contains steps to set up and run the web plugin locally for deepseek-harness.

Prerequisites
- Node.js (recommended >=18)
- npm

Steps
1. Install pnpm (if not installed):
   npm install -g pnpm
2. From the repository root, install dependencies:
   pnpm install
   Note: The workspace is large; use a stable network or a registry mirror if you see many ECONNRESET/UND_ERR_SOCKET errors.
3. Start the web dev server:
   npm run dev:web

Troubleshooting
- If pnpm install fails with registry/network errors, retry on a trustworthy network or configure a registry mirror (e.g., npmrc).
- For esbuild native tarballs, ensure your platform is supported or use an appropriate prebuilt binary.

If you want, I can run the install again or open a pull request including this doc. (Recommended: run pnpm install locally after ensuring network stability.)
