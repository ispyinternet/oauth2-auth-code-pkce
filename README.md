# OAuth2AuthCodePKCE client

forked from https://github.com/BitySA/oauth2-auth-code-pkce

## Changes

Default via config and allow user to specify whether to *rememberSession*

If `false`, refresh tokens are ignored and oauth state is only persisted to
sessionStorage

If `true` oauth state is persisted to localStorage and refresh tokens are saved
so creating a long-lived session
