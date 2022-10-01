# OTP 

[![Build Workflow](https://github.com/sshyran/otp/workflows/Build%20&%20Deploy/badge.svg)](https://github.com/sshyran/otp/actions)

## 1. Offline-ready OTP WebApp
This WebApp may safely remain in YOUR GitHub-pages enabled forked repo, and in YOUR pinned browser tab as long as YOU wish! Fork and try it on some dummy (disposable)  email/account/service before applying/encoding your real account with this Web-OTP app! 

### 2. With this app, in some cases, you may set yourself free from platform/provider/device OTP lock and forced OTP-optins! But to achieve this, you MUST NEVER lose access to your initial OTP setup QR-codes (coz they serve as OCR-keys for this in-memory webapp), even if OTP device (your phone or hardware key) is lost! So... personal, password-protected cloud image service/storage seems good to go, probably ; ) 

## 3. Major drawback: 
This client-side WebApp can only eliminate software installation necessity and/or physical OTP-hardware posession/presence at hand. But, IT DOES NOT store your OTP QR-codes in-memory (it has no internal database, you won't see the list of your OTP-ed resources after page refresh). 
#### Therefore, to prevent OTP-access-lock on some websites (they show QR-code only once, at initial setup stage): 
* generate text backup codes (or phrases) immediately after OTP login! 
* save your initial OTP login QR-code separately in a safe place!
* take screenshots and save them in your private, password-protected cloud storage !
* feed this app with your website-specific QR-image each time you login, then wait a few seconds for this app to regenerate a new login code, copy-paste-login!
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
* originally developed and generously provided by @qoomon 
* tested and experimented on by @sshyran
