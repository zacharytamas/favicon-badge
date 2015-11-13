# favicon-badge

An element for declaratively updating the favicon for your webapp with dynamically-set numbers. Powered by [Favico.js](https://github.com/ejci/favico.js).


## Dependencies

Element dependencies are managed via [Bower](http://bower.io/). You can
install that via:

    npm install -g bower

Then, go ahead and download the element's dependencies:

    bower install


## Developing

If you wish to work on `favicon-badge` in isolation, I recommend that you use
[Polyserve](https://github.com/PolymerLabs/polyserve) to keep your element's
bower dependencies in line. You can install it via:

    npm install -g polyserve

And you can run it via:

    polyserve

Once running, you can preview your work at
`http://localhost:8080/components/favicon-badge/`, where `favicon-badge` is the name of the directory containing it.


## Testing

Simply navigate to the `/test` directory of the element to run its tests. If
you are using Polyserve: `http://localhost:8080/components/favicon-badge/test/`

### web-component-tester

The tests are compatible with [web-component-tester](https://github.com/Polymer/web-component-tester).
Install it via:

    npm install -g web-component-tester

Then, you can run the tests on _all_ of your local browsers via:

    wct

#### WCT Tips

`wct -l chrome` will only run tests in chrome.

`wct -p` will keep the browsers alive after test runs (refresh to re-run).

`wct test/some-file.html` will test only the files you specify.
