# journeyfy-links

Static invite-link redirector for the [Journeyfy](https://github.com/FranDesarrolladorWeb/Journeyfy) iOS app.

Messengers like WhatsApp only auto-link `https://` URLs, so invites point here
(`/join/?token=…`) and this page bounces to the `journeyfy://join?token=…`
deep link that opens the app.

Future: host `.well-known/apple-app-site-association` here (or on a custom
domain) to upgrade these to Universal Links.
