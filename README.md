# OmegaT Website

## MOOC.FI Review

This branch gets automatically deployed on push to https://omegat-site.onrender.com/

This is the website for OmegaT, the best computer-assisted translation tool. You can access the actual website here: <https://omegat.org/>.

The website is built with Jekyll.

## Development

An easy way to quickly test changes you've made to the website is to use docker as a local server.
Navigate to the root folder of the project. You can build the image by running:

```bash
docker build -t omegat-site:dev .
```

If the build succeeds, you can then start a container by running:

```bash
docker run -p 10000:10000 omegat-site:dev
```

You can then access the website locally at `localhost:10000` or `http://127.0.0.1:10000`

You can kill the server using the <kbd>Ctrl</kbd> + <kbd>C</kbd> shortcut in the CLI.
