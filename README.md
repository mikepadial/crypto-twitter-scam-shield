<img src="https://lh3.googleusercontent.com/M4uQN2xTiN1X6Z-nHiCuxvbgZkd-9cMVzUXWhkDFO2p6yhV-K82Ej8pnQMsGrWQhHgxfO5A9P17uAlsgshtbY07H27Q=s1280-w1280-h800" alt="example" width="500">

---

Install extension - https://chromewebstore.google.com/detail/crypto-twitter-scam-shiel/jncnooeffigcacclopoekhabeocbhbij?hl=en-GB&utm_source=ext_sidebar

## Overview

A Chrome extension that protects users from **typosquatting attacks** and potential financial loss.

- **Real-time Account Verification**: Automatically highlights account names as you scroll through social media
  - 🔴 Red highlighting for accounts the you do not follow
  - 🟢 Green highlighting for accounts that you follow
   

## Architecture

- **Frontend**: Chrome extension built with React, Typescript, Vite and TailwindCSS. CSS is injected into the DOM on scroll to highlight account names red or green.
- **Backend**: AWS Lambda serverless function and API gateway that abstracts the Twitter API used to fetch the list of accounts the user follows.


## Examples of typosquatting

https://www.publish0x.com/spamreports/beware-of-twitterx-gold-verified-scams-xmjmnrn


<img src="https://cdn.publish0x.com/prod/fs/cachedimages/4046878907-38fd983dc06948ef2aa24beaf75462b03ee1489bb4e5732c07378d2ffbdf10a4.webp" alt="example" width="700">
