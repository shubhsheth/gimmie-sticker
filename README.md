# CougarCS Git Workshop: Zero to Hero

This project provides a CLI script that allows you to encrypt your mailing address with a public key. I can then decrypt it with my private key and mail you a sticker.

## Workshop Date: Nov 5, 2020 from 7pm - 8:30pm

No pull requests will be accepted before the event starts.

## Instructions

Note: You must have Node 8 or later installed locally.
Note: Your commit must contain **only 1 file**. Verify that you did not change any existing code before making your PR.

1. `fork this repo`
1. `git clone` your fork url
1. Enter the project and run `npm install && git checkout -b mysticker`
1. `npm run address` and enter your address carefully OR encrypt your address here: https://wonderful-edison-6f2992.netlify.app/.
1. Copy the encrypted address to a new file in `/stickers/<your-github-username>.txt`
1. `git add . && git commit -m <your-message>`
1. `git push origin mysticker`
1. Open new pull request on Github
1. Wait 1 to 2 weeks for the sticker 💌

## Working

You can have a look at the inner workings [here](working.md).

## Credits

This repo was clone from [here](https://github.com/codediodeio/gimmie-sticker). The inspiration for this workshop comes from this [video](https://youtu.be/HkdAHXoRtos)