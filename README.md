# Perl (PSGI) Hello World

Hello World is a simple web application to use as an introduction to Vorteil running on NGINX Unit. It hosts a webpage containing a simple hello world message with Vorteil's logo. The background colour of the page can be controlled by setting the `BACKGROUND_COLOUR` environmental variable to any valid HTML colour code.

No changes were needed for the [NGINX Unit platform!](https://unit.nginx.org/)

## Running

The helloworld web appliction requires a `BACKGROUND_COLOUR` environmental variable

```sh
BACKGROUND_COLOUR=#FF0000
helloworld.psgi
```

The environmental variable colour: must be six characters of hexadecimal (like '#FFFFFF')

