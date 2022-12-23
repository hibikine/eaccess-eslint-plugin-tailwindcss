# eaccess-eslint-plugin-tailwindcss

When using `tailwindcss/no-custom-classname` rule in `eslint-plugin-tailwindcss`, an EACCES error occurs if a non-readable directory exists.

## Requirements

- Node.js
- npm

## Steps

1. `git clone https://github.com/hibikine/eaccess-eslint-plugin-tailwindcss`
2. `cd eaccess-eslint-plugin-tailwindcss`
3. `npm ci`
4. `npm run start` and throws EACCES
