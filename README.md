# Deno vendor JSX bug

## Steps to reproduce

1. Clone this repository
2. Run `deno run main.tsx` which will print `<h1>it works</h1>`
3. Run `deno venodr main.tsx`
4. Run `deno run --no-remote --import-map=vendor/import_map.json main.tsx`
