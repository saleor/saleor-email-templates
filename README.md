# Saleor Email Templates

The sample templates for emails are located in `templated_email`.

The `source` directory contains [MJML](https://mjml.io/) templates. Those `.mjml` files need to be compiled to HTML and put into the `compiled` directory before they can be used.

To compile the emails you need to have Node.js 10.x or later installed. See the [Node.js installation instructions](https://nodejs.org/en/download/package-manager/) for instructions.

Saleor uses [Handlebars](https://handlebarsjs.com/) as a templating language.

You also need to install Saleor's frontend dependencies first. To do that run:

```shell
npm install
```

To compile the emails run:

```shell
npm run build-emails
```

