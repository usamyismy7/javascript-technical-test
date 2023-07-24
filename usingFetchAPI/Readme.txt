Hello!

this html file can only run using web server, I am using VS Code's extension "Live Server" by "Ritwick Dey" to serve the html file.

if you want to run html file directly on the browser please open usingSimpleHTML folder and run html file directly without using any web servers.

Thank You

---------------why html file cannot run directly ?---------------

When you directly open an HTML file in a browser using the file:// protocol, it can sometimes lead to cross-origin issues or restrictions due to security policies implemented by modern web browsers. These restrictions are in place to prevent malicious scripts from accessing local files on a user's system.

To bypass these restrictions, you can either serve the HTML file through a web server or use a tool like Live Server extension in VS Code, which sets up a local server to serve your HTML file.