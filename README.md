# BS5 Client Extension

This client extension adds Bootstrap 5.3.3 by CDN include in `main.scss`.
It also includes the Token Definition with the 117 custom properties (tokens) provided in BS5.
Dark tokens stylebook is here: https://github.com/marcoscv-work/BS5-dark-style-books (right not we cannot include them in the same Client Extension).

You can use the compiled file on `dist\` directory, just move it to your `deploy` DXP 7.4 directory.

It removes all duplicities between the original BS4 used in Clay and BS5.

If you need to add more Clay components, you can just uncomment the lines on:
`clay/_components.scss`:
