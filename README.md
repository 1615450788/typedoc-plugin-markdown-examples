# typedoc-plugin-markdown-examples

## Publishing to Docusaurus

### 1. Clone the repo

```shell
git clone https://github.com/tgreyuk/typedoc-plugin-markdown-examples.git
```

### 2. Install docusaurus

See https://docusaurus.io/docs/en/installation#installing-docusaurus

Install docusaurus in root directory of the clone

```shell
npx docusaurus-init .
```

### 3. Run docs script

Publish the docs from root of clone

```shell
npm install

npm run docs
```

### 4. Running the website

See https://docusaurus.io/docs/en/installation#running-the-example-website

```shell
cd website

npm start
```

### 5. Viewing the website

The example Docusaurus website will be available at http://localhost:3000/docs/myapi/.

Manually add the index page to headerLinks it siteConfig.js to access the api from header.

```js
headerLinks: [
  { doc: "myapi/index", label: "My API" },
],
```
