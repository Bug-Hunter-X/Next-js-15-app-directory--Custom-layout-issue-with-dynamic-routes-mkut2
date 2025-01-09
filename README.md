# Next.js 15 App Directory Custom Layout Issue with Dynamic Routes

This repository demonstrates an unexpected behavior in Next.js 15's App Directory when using a custom layout with dynamic routes.  The issue arises when navigating between pages that share the same layout but have different data.

## Bug Description

The layout doesn't correctly re-render when navigating between dynamic routes even when the data changes. This leads to stale data being displayed on the page.