<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://ai.google.dev/static/site-assets/images/share-ais-513315318.png" />
</div>

# USB Backup Verification Utility

A local-only React application for comparing an original file collection with a USB backup using CRC-32 checksums. Files are read in the browser and are not uploaded to a server.

## Run Locally

**Prerequisite:** Node.js 18 or newer


1. Install dependencies:

   ```powershell
   npm.cmd install
   ```

2. Start the Vite development server:

   ```powershell
   npm.cmd run dev
   ```

3. Open http://localhost:3000/ in your browser.

Do not use the VS Code Live Server extension for this project. Live Server cannot transform the TypeScript/React entrypoint. Use the Vite command above instead.

### PowerShell note

If `npm` is blocked by the PowerShell execution policy, use `npm.cmd` as shown above. This does not require changing the system execution policy.

## Validate a Build

```powershell
npm.cmd run lint
npm.cmd run build
```
