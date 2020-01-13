# svelte-tailwindcss-template

Using [a better approach](https://dev.to/sarioglu/using-svelte-with-tailwindcss-a-better-approach-47ph) and `.prettierrc.json` and `.eslintrc.json` from [this article](https://dev.to/ilia_mikhailov/svelte-tailwind-parcel-awesome-4891#extra-bonus-basics).

## Customize

[Google Fonts in Tailwind](https://scottw.com/blog/google-font-tailwind/)

## Util

Filter `npm run dev` for stderr only: `npm run dev 2 > 1 > /dev/null` (useful in tmux; this is fis shell, for bash use [this](https://stackoverflow.com/questions/2342826/how-to-pipe-stderr-and-not-stdout)  )

Check 'quiet' amd 'silent' in package.json scripts:

```json
"dev": "rollup -c -w --silent",
"start:dev": "sirv public --single --dev --quiet"
```

[Tailwind Cheat Sheet](https://nerdcave.com/tailwind-cheat-sheet)

