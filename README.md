# OTP 

[![Build Workflow](https://github.com/sshyran/otp/workflows/Build%20&%20Deploy/badge.svg)](https://github.com/sshyran/otp/actions)

## Offline-ready OTP WebApp. 
Set yourself free from platform/provider/device OTP lock! NEVER lose access to OTP-ed resources, even if OTP device is lost! BECAUSE this WebApp may safely remain in YOUR GitHub-pages enabled repo as long as YOU wish! Fork and enjoy!
## Major drawback: 
#### It does not store your OTP QR-codes in-memory (you won't see the list of your OTP-ed resources after page refresh). Therefore, to prevent OTP-lock on some websites (they show QR only once), generate backup codes immediately after OTP login, and save your initial OTP login QR-codes separately in a safe place, or take screenshots! You've been warned ! ; )

## ☂️ No External Services are used, local JavaScript execution only ☂️

Hosted at github pages: https://sshyran.github.io/otp/
* branch: [gh-pages](https://github.com/sshyran/otp/tree/gh-pages)

Or host it on your onw GitHub account 
* Just fork this repo and this web app is available at:
  
  [https://\<USERNAME>.github.io/otp/](https://USERNAME.github.io/otp/)


### Features
* generate TOTP codes
* show remaining valid seconds for totp code
* generate QR-code with OTPAuth URL
  * click on QR-code to copy OTPAuth URL
* parse OTPAuth URLs in the `secret` input field
  * e.g. `otpauth://totp/john.doe?secret=N2SJSUOXCKQM5MAX7N7J3NBUQ4WTL66G&issuer=example.org`
  
## Developer Notes
* https://csscomb.herokuapp.com/online
* originally developed and generously provided by @qoomon 
