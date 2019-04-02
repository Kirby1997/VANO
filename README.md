# VANO (BETA)
A NANO light-wallet browser extension. It works with  NANO, a fast & fee-less currency secured by a decentralised network. The wallet stores all sensitive data locally (encrypted) and never communicates it to a server. 

**VANO is still in beta, *do not* store large amounts of NANO on this wallet!**

![Dashboard](https://github.com/marekhoeven/VANO/blob/master/dashboard.png)

## Deeplink support
The extension requires read/write access to allow for deeplink recognition on a browser. If detected, clicking on a deeplink will automatically open a popup with the amount & address filled in, ready to be send. This feature currently only works for Chrome/Brave users (showing a popup on firefox seems to be difficult). 

You can test deeplinks on my [DEMO page](https://marekhoeven.github.io/deeplink/). 

## Todo

- Add addressbook (alias system?)
- Optimalisation of JS functions
- Improve some shitty CSS (on components and globally)
- Documentation + better structure 
- Set user-option for minimum receive amount
- Perhaps select what individual pendings to accept?


## Acknowledgements

Special thanks to the following repo's. You made the creation of this extension a lot easier. Thank you!

- [Kocal/vue-web-extension](https://github.com/Kocal/vue-web-extension) - Vue-web-extension template
- [cronoh/nanovault](https://github.com/cronoh/nanovault) - Nanovault wallet
- [numtel/nano-webgl-pow](https://github.com/numtel/nano-webgl-pow) - WebGL PoW Implementation
- [jaimehgb/RaiBlocksWebAssemblyPoW](https://github.com/jaimehgb/RaiBlocksWebAssemblyPoW) - CPU PoW Implementation
- [dcposch/blakejs](https://github.com/dcposch/blakejs) - Blake2b Implementation
- [dchest/tweetnacl-js](https://github.com/dchest/tweetnacl-js) - Cryptography Implementation

## Donate

If you like what I've made and/or are feeling generous, you can donate to me at
`xrb_3tfccg1pfr9k8o548jb6bj9fyyc4mmhnpepounzneobfwuq8won9enactbkk`
