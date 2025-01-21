# Node.js Server Unresponsiveness

This repository demonstrates a common issue in Node.js servers: unresponsiveness due to long-running operations within the request handler.  The `bug.js` file shows a server that hangs for 5 seconds in each request.  This blocking behavior can lead to poor performance and prevent other requests from being processed.

The `bugSolution.js` file shows the solution using asynchronous operations and promises to prevent this blocking issue. This solution uses asynchronous I/O operations to prevent the event loop from being blocked.