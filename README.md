# Next.js 15 App Router: Pages Directory Not Found (404)

This repository demonstrates a common issue encountered when migrating to Next.js 15's App Router:  the inability to access pages within a traditional `pages` directory.

## Problem

When using the App Router, Next.js 15 primarily relies on the `app` directory for routing.  Attempting to access a page located in the `pages` directory results in a 404 error.

## Solution

The solution is to move all page components from the `pages` directory to the `app` directory or use a different routing approach for legacy pages.

## Setup

1. Clone this repository.
2. Run `npm install`.
3. Run `npm run dev`.

You will encounter a 404 error when trying to access the home page because it is still placed in the `pages` directory. The solution file shows how to resolve this issue.
