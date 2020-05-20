# UtilityBeltKeychain

This was a project under development within our [https://github.com/spothero/UtilityBelt-iOS](UtilityBelt) package suite that Brian Drelling started dabbling with when looking to reduce dependency bloat across our application, driven by an aggressive migration over to Swift Package Manager in late 2019. At the time, SpotHero was using a poorly maintained Keychain library that didn't support SPM and it seemed like a good time to remove it. Brian explored writing a small wrapper around Keychain himself, but discovered  [KeychainAccess](https://github.com/kishikawakatsumi/KeychainAccess) which had SPM support and everything SpotHero needed, with the bonus of significant community engagement and support.

Though the code in this project was developed in only a few days, we saw no need to continue with the effort.

At the time of writing, WWDC 2020 promises to bring some new iOS 14 Keychain functionality. Maybe that'll finally include a good, first-party Keychain framework for developers? Time will tell.
