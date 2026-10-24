# reports

Encrypted reports published by [trip-builder](https://github.com/nahueltaibo/trip-builder).

Every page under `r/` holds only AES-256-GCM ciphertext. The key travels in the share link's
`#k=...` fragment, which browsers never send to the server, so this repository and GitHub Pages
can't read the reports. Without the full link there is nothing to see here.
