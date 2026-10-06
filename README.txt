# SGX App Maker — PWA Package

This folder contains the PWA-ready version of your current SGX App Maker HTML.

## Files
- index.html — your current SGX App Maker, updated for PWA support
- manifest.json — install/app metadata
- service-worker.js — offline app-shell caching
- offline.html — offline fallback page
- icons/icon-192.png — PWA icon
- icons/icon-512.png — PWA icon

## Install
A PWA service worker requires HTTPS (or localhost). Upload this whole folder to an HTTPS web host, then open the site on Android and use the browser's "Install app" / "Add to Home screen" option.

## Gemini AI
The AI feature still calls Gemini from the browser. Keep in mind that a browser-side API key can be exposed to users. For a public app, use a server-side proxy/backend rather than shipping a secret API key in client code.
