# Girl Psychology Simple Automation — informational website

Static informational homepage and privacy policy for the channel owner's desktop publishing workflow.

## Public site contents

- `index.html`: application identity, purpose, authorization boundaries and contact.
- `privacy.html`: privacy policy and Google/YouTube data handling boundaries.
- `styles.css`: responsive, local-only stylesheet.
- `.nojekyll`: serve static files directly on GitHub Pages.
- `.gitignore`: exclude credential/configuration and private working files.

There is no web backend, public sign-up, Google sign-in form, JavaScript tracker or credential collection on this site. YouTube OAuth is a separate local desktop flow and is not configured merely by publishing these pages.

## Security boundary

Never commit OAuth client configuration, access or refresh tokens, passwords, browser state, local automation logs or unpublished video assets. Upload only the explicitly reviewed static website files. The public contact email was authorized by the operator.

## Google setup

After deployment, verify the actual public homepage and privacy URLs before entering them in Google Cloud Branding. Verify ownership of the account-controlled Pages address in Google Search Console with an approved HTML file or meta-tag method. Obtain the real verification value from Google; never fabricate it.

Free static hosting does not itself prove Google has accepted the domain, approved branding, verified OAuth scopes, granted YouTube API publishing eligibility, or connected the channel. Keep each of these checks separate.

This repository does not contain the desktop automation implementation or any account credentials.
