# Gibbon-pdf backend

## Getting started

Install dependencies:

```
$ yarn install
```

You can watch the project:

```
$ yarn run watch
```

## Tests

For now tests must be run inside a docker container with image
`node:14.16.0-alpine3.13` to keep the same version of chromium that generate pdf

```
$ ./scripts/test.sh
```
