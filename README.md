made by !yeti
```
!yetiluk
```
---

## install (one time)

1. download node.js: https://nodejs.org/en → install
2. download git: https://git-scm.com → install
3. open powershell → run: `npm install -g pnpm`
4. open powershell → run:
   ```
   git clone https://github.com/Vendicated/Vencord
   cd Vencord
   pnpm install
   pnpm build
   ```
5. close discord
6. run: `pnpm inject`
7. pick your discord → done

## add custom plugins

1. create folder: `Desktop\custom-plugins`
2. put plugin files/folders inside
   - example: https://github.com/BlockTol/Quest-Auto-Complete
   - clone it: `git clone https://github.com/BlockTol/Quest-Auto-Complete` into custom-plugins
3. go to vencord folder:
   ```
   cd Vencord
   pnpm build
   ```
4. close discord
5. run: `pnpm inject`
6. reopen discord

## update (every time)

1. open powershell in vencord folder
2. run:
   ```
   git pull
   pnpm install
   pnpm build
   ```
3. close discord
4. run: `pnpm inject`
5. reopen discord

## links

- vencord: https://github.com/Vendicated/Vencord
- node.js: https://nodejs.org/en
- git: https://git-scm.com
- pnpm: https://pnpm.io
- quest auto complete: https://github.com/BlockTol/Quest-Auto-Complete
- video: https://www.youtube.com/watch?v=XmVNRKrphlw
