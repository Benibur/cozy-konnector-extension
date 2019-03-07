# Cozy konnector browser extension

A browser extension to help build Cozy konnectors.

1. [x] Interactive REPL to quickly see what you are scraping
2. [x] Mouse selection to get selectors 
3. [x] Saving REPL in localStorage
4. [ ] Save page by page
4. [ ] Generate a konnector from the playground
5. [ ] Access to default parsers
6. [ ] Load a konnector in the extension

## Installation

The extension is in development mode and has not been published to the
Chrome store yet.

```bash
$ git clone git@github.com:cozy/cozy-konnector-playground.git
$ cd cozy-konnector-playground
$ yarn
$ yarn build
```

This will create the `dist/` folder with the files bundled ready to be installed in Chrome.

### Chrome

1. Go the extension settings (Menu > More tools > Extensions)
2. Toggle the developer mode
3. Load unpacked extension > Choose the `dist/` folder

✨You now have the "Konnector" panel in your Chrome devtools.

### Firefox

The extension is planned to worked in Firefox and Chrome but since there are small API differences between the two, it does not work yet in Firefox. PRs are welcome ;)
