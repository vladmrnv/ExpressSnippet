# ExpressSnippet
A collection of snippets for Express.js (https://github.com/expressjs)

To initiate just type out express commands and the rest will be autocompleted.

**Work In Progress**

![](http://i.imgur.com/1pATOUW.gif)

# Snippets
Command | Description
---|---
app.all|This method is like the standard app.METHOD() methods, except it matches all HTTP verbs.
app.disable|Sets the Boolean setting name to false, where name is one of the properties from the app settings table.
app.disabled|Returns true if the Boolean setting name is disabled (false), where name is one of the properties from the app settings table.
app.get|Express GET request
app.listen|Binds and listens for connections on the specified host and port. This method is identical to Node's http.Server.listen().
app.param|Add callback triggers to route parameters, where name is the name of the parameter or an array of them, and callback is the callback function.
app.patch|Routes HTTP PATCH request to the specifed path with the specified callback functions.
app.post|Express POST request
app.put|Express PUT request
app.delete|Express DELETE request
app.render|Returns the rendered HTML of a view via the callback function. It accepts an optional parameter that is an object containing local variables for the view.
app.route|Returns an instance of a single route, which you can then use to handle HTTP verbs with optional middleware. Use app.route() to avoid duplicate route names (and thus typo errors).
app.set|Assigns setting name to value, where name is one of the properties from the app settings table.
app.use|Mounts the specified middleware function or functions at the specified path. If path is not specified, it defaults to “/”.
res.send|Express RESPONSE object

## Links
[Github](https://github.com/vladmrnv/ExpressSnippet)
[VS Code](https://marketplace.visualstudio.com/items?itemName=vladmrnv.expresssnippet)

## License
MIT License

Copyright (c) [2017] [Vlad Marinov]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
