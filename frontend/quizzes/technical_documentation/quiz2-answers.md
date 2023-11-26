Check out the documentation at https://create-react-app.dev/docs/getting-started. There’s a lot to read 
there, and you won’t have to read through all of it. This quiz will test your ability to navigate a 
large suite of documentation to find answers to some questions. Each question has a clear part of the
documentation to find the answer, but additional information outside the documentation might be
useful to fully understand what the documentation is saying.

1. Configuring the `IMAGE_INLINE_SIZE_LIMIT` environment variable with a value of `0` will disable the inlining of images in the CSS or Javascript files when the project builds.

See https://create-react-app.dev/docs/advanced-configuration/
 
2. An environment variable like `REACT_APP_BACKEND_API_URL` is accessed by the Javascript code using
the `process.env` object. The code `process.env.REACT_APP_BACKEND_API_URL` will return the value of the
environment when the project was built.

See https://create-react-app.dev/docs/adding-custom-environment-variables/

3. The first step to use Sass with a create-react-app project is to install the sass package with
`npm install sass`. This will allow the project to build .sass files into .css stylesheets. Once 
that step is done, the src/App.css file will need to be renamed to src/App.scss and src/App.js will need 
to import src/App.scss.

See https://create-react-app.dev/docs/adding-a-sass-stylesheet

4. A project might not deploy correctly on Github Pages for a few reasons. The first would be a
missing `homepage` entry in the package.json with the url for the app. The second would be that the
project repository is not correctly configured for gh-pages.

Another reason would be getting a "/dev/tty: No such a device or address" error on deploying. For this
error, try creating a new access token and reconfiguring the project’s origin with the token.

Yet another reason mentioned in the docs would be getting an error that says "/dev/tty: No such a device 
or address". Try setting an email and username in the project’s git config and deploying again.

See: https://create-react-app.dev/docs/deployment#github-pages 

5. When using Netlify to host a create-react-app project, the project needs a `public/_redirects` file.
That file should contain the following code
```
/*  /index.html  200
```

As an extra special double bonus secret question, what does the documentation mean when it calls this a “rewrite rule”?

Extra Credit:

The `npm run eject` script allows for more customization of how a create-react-app project is built.
A default configuration of a create-react-app project has multiple build dependencies that are used
to build it. These are grouped together and hidden away from the developers of a project, but are
actually different packages. Some of these are Webpack, Babel, and ESLint. Webpack is the project that
manages the overall build process. Babel is a compiler that translates TypeScript, JSX, and React.js
files into native Javascript. ESLint is used to check for errors in Javascript code and format JS files.

Once eject is run, these are all split out so they can be configured independently for larger projects
with more complex build requirements. Running it can only be done once, and doing so removes the
`npm run eject` script from the project. However, version control can always be used to restore to a
previous state.