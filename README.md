# inline-moodle-pdf-extension

Chrome extension which makes the MOOC Helsinki platform show PDF downloads in a new tab instead of downloading them.

Works by rewriting `Content-Disposition: attachment` into `Content-Disposition: inline` in PDF web requests. See [`./background.js`](https://github.com/cxcorp/inline-mooc-pdf-extension/blob/master/background.js) for details.

## License

MIT License, see LICENSE.
