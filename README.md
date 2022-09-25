# OTP 

[![Build Workflow](https://github.com/sshyran/otp/workflows/Build%20&%20Deploy/badge.svg)](https://github.com/sshyran/otp/actions)

## 1. Offline-ready OTP WebApp
This WebApp may safely remain in YOUR GitHub-pages enabled repo as long as YOU wish! Fork and enjoy! 

## 2. With this app, in some cases, you may set yourself free from platform/provider/device OTP lock and forced OTP-optins! But to achieve this, you MUST NEVER lose access to your initial OTP setup QR-codes, even if OTP device (phone/key) is lost! 
## 3. Major drawback: 
This client-side WebApp can only eliminate software installation necessity and/or physical OTP-hardware posession/presence at hand. But, IT DOES NOT store your OTP QR-codes in-memory (it has no internal database, you won't see the list of your OTP-ed resources after page refresh). 
#### Therefore, to prevent OTP-lock on some websites (they show QR only once, at setup stage: 
* generate text backup codes (or phrases) immediately after OTP login! 
* save your initial OTP login QR-code separately in a safe place!
* take screenshots and save them in your private, password-protected cloud storage !
* feed this app with your website-specific QR-image each time you login!
* If it all seems too hard or not safe enough - use SMS-based OTP (only if you trust your phone number provider, and operator has your identity confirmed) or don't mess with OTP's at all !
* You've been warned !   ; )

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
