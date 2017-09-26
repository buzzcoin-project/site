# site

## development

### get started

make sure you have node installed.

run the commands from within the project root.

```
npm install
```

This will install of the necessary dependencies.

### style generation

the website currently uses scss to generate css styles.

there are two related scripts.

the first is `npm run watch` which will live compile scss changes into css.

Simply edit the scss files related to the changes you are making and save them, then reload in the browser and your changes will be present.

The second is `npm run build`, which does the same as the "live compiling", but is done only once. This is to be done before any deployment of changes to ensure that the css updates are on the latest version.