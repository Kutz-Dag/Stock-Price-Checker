# Stock Price Checker

### Preview

![messageboard](https://github.com/user-attachments/assets/86e8c84b-e23f-43ce-b03d-9daf479f7258)

#### Description

Build a full-stack JavaScript app that is functionally similar to the preview above. Click on the preview to be directed to a render.

Write the following tests in tests/2_functional-tests.js:

- Creating a new thread: POST request to /api/threads/{board}
- Viewing the 10 most recent threads with 3 replies each: GET request to /api/threads/{board}
- Deleting a thread with the incorrect password: DELETE request to /api/threads/{board} with an invalid delete_password
- Deleting a thread with the correct password: DELETE request to /api/threads/{board} with a valid delete_password
- Reporting a thread: PUT request to /api/threads/{board}
- Creating a new reply: POST request to /api/replies/{board}
- Viewing a single thread with all replies: GET request to /api/replies/{board}
- Deleting a reply with the incorrect password: DELETE request to /api/replies/{board} with an invalid delete_password
- Deleting a reply with the correct password: DELETE request to /api/replies/{board} with a valid delete_password
- Reporting a reply: PUT request to /api/replies/{board}

#### User Stories/Tests to pass 



