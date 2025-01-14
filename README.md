# bitcoinblackfriday.org

Site for posting Bitcoin related black friday deals. The `docs/` dir contains
all the static content.  This is because GitHub pages supports hosting the
`docs/` subdir.

## Contributors

To contribute a deal to Bitcoin Black Friday:

1. Clone this repo.
2. Edit the `deals.json` file, add your own deal.
3. Include an image in the `images/` directory.
4. Run the site locally to confirm your deal looks as it should.
5. Submit a PR.

## Running Locally

First install Node.js, then install dependencies:

```
$ npm install
```

To run the site locally on the default port, 8080:

```
$ npm start
```

This will launch a simple, static HTTP server serving the `docs/` directory.
Open a browser to `localhost:8080` to see the site.

## Landing Page

comment out `landing-page` full `<article>` to make the rest come up. 

## Demo of Listing

![bbf-screen-shot](https://user-images.githubusercontent.com/797193/140234885-d9e5488a-9848-4522-8d4e-8f185ecd554a.png)
