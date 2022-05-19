Ques: What happens when a URL is entered in the browser?

Ans: When a URL is searched in the browser, the following action takes place:

1. Browser searches for IP address with the help of DNS servers.

2. From the IP adress, browser determines the server location and domain information.

3. Browser establishes a TCP connection with the server to access the .htm,.css, .js and other media files, by sending HTTP request.

4. Once .htm, .css, .js files are retrieved by the browser, it happens to send these information to render engine.

5. The render engine parses .htm data to create DOM - Document Object Model.

6. The render engine parses .css and .js data to create CSSOM.

7. Both DOM and CSSOM creates forms a node tree which is a layout structure for the render engine to process.

8. The render engine then read these nodes and print/paint/display the web page.

Process Diagram: https://www.canva.com/design/DAFAY0fRxCI/TzGT3o4BNviHu9RuY5ZXhw/edit?utm_content=DAFAY0fRxCI&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
