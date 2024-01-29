# Bug demo: calling redirect from an React Server Component to an intercepted route causes infinite rerendering loop

## How to play this demo

1. Clone the repo / Open codespaces
2. npm install
3. npm run dev
4. Click the link on the main page
5. Watch the browser console or the terminal: the component that renders the intercepted route will be stuck in the rerendering loop

## Environment

Tested:
- with babel / without babel
- on mac os / on github codespaces
- with turbopack / without turbopack
- on canary / on stable
- with bun / with node
