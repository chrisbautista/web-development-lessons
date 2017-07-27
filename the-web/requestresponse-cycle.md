# Dissecting a Request/Response Cycle

These are steps in:

1. User types a URL into the address bar of a browser
2. Browser looks up the **IP/Internet Protocol** address of the URL
   * IP is a kind of phone number that identifies the machine that serves that address
   * People are better at remembering words than numbers
3. Address is sent to a **DNS server**, which is a directory of all machines connected to the internet
3. **DNS server** will send a response to the browser with the corresponding IP if found.
4. Browser then sends a request to the machine with that IP. 
5. If all goes well, server responds with message with a HTTP Header of 200 OK and followed with the HTML document. 