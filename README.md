# netlify-auth-providers

A JavaScript library to use Netlify's OAuth providers, it relies on a popup (which may cause issues on mobile or with popup blockers e.g. in Firefox).


You can check an example React implementation/usage here: https://github.com/kentcdodds/react-github-profile/blob/b0c6a4628535fcea32f4f6617efd03f6b29574f4/src/github-client.js#L1

Full setup instructions can be found in the [Netlify OAuth provider docs](https://www.netlify.com/docs/authentication-providers).


## List of Alternatives

**Lowest level JS Library**: If you want to use the official Javascript bindings to GoTrue, Netlify's underlying Identity service written in Go, use https://github.com/netlify/gotrue-js

**React bindings**: If you want a thin wrapper over Gotrue-js for React, `react-netlify-identity` is a "headless" library, meaning there is no UI exported and you will write your own UI to work with the authentication. https://github.com/sw-yx/react-netlify-identity

**High level overlay**: If you want a "widget" overlay that gives you a nice UI out of the box, with a somewhat larger bundle, check https://github.com/netlify/netlify-identity-widget

**High level popup**: If you want a popup window approach also with a nice UI out of the box, and don't mind the popup flow, check https://github.com/netlify/netlify-auth-providers
