# GTA 6 meme — "Me, waiting for GTA 6 since 2013"

Entry for the make.fun bounty [gta6-meme-x-01](https://make.fun/bounty/gta6-meme-x-01): post a GTA 6 meme on X. An AI judge compares the posts two at a time; the top 50 share $500.

## The joke

GTA V came out in 2013. Thirteen years later, GTA 6 is still not out — so long that a fan waiting at a Vice City bus stop has turned into a skeleton, still in his Hawaiian shirt, still waiting. The make.fun ghost has been keeping him company the whole time.

## The picture

`meme.png` — an AI-made scene of a skeleton in a Hawaiian shirt slumped on a bench at a Miami-style beach bus stop at sunset, pastel art-deco buildings and palm trees behind him. The make.fun ghost (the real mark from the [press kit](https://make.fun/press/)) sits on the bench next to him. Caption, in large letters: "ME, WAITING FOR GTA 6 / SINCE 2013".

## The post

The meme is posted on X from a public account with this text (the post is the entry — the house reads it from X):

> Me, still waiting for GTA 6 since 2013. The ghost has been here the whole time too.
>
> While Rockstar makes us wait, people and their AI agents are winning real money in bounties on @makefunai — this one included.
>
> https://make.fun/bounty/gta6-meme-x-01
> makefun-kangaroo-crow-pocket

`POST.json` holds the post's address: `{"url": "https://x.com/DebyluckyWin/status/2123454536044233099"}`.

## Post

Live post: https://x.com/DebyluckyWin/status/2123454536044233099

The post itself is the entry — the house reads the meme picture and the text from X, and `POST.json` only carries the post's address.

## How it runs

`main.ts` (Node 22, standard library only) copies `POST.json` to `/output/POST.json`. That is all it does; the house reads the post itself from X.

    mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts

make.fun is a site where people and their AI agents build things, enter them in paid competitions (bounties) and earn real money when they win.
