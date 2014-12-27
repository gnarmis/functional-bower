# Functional Bower

A packaging of Oliver Steele's
[Functional Javascript library][functional-js-oliver] into a Bower component.
Version `1.0.2`, btw.

I used the files in [this Node.js port][functional-node] and used `browserify`
to bundle them up and put that bundled up javascript in `dict/`.
Use `./build.sh`.

## Usage

`bower install functional-bower`

Then, you have to link to that javascript file in `dist/` in your html file,
or otherwise make use of it in a client-side context.

This will be a browserify-style module, which is a universal (kinda) way of
packaging and using modules (apparently).
[Read more about universal module definitions][browserify-modules].

[functional-js-oliver]: http://osteele.com/sources/javascript/functional/
[functional-node]: https://github.com/bailus/functional-node
[browserify-modules]: http://dontkry.com/posts/code/browserify-and-the-universal-module-definition.html