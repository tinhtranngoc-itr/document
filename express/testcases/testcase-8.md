---
puppeteer:
  headerTemplate: |
    <html>
      <div style="display:flex; width:100%; margin: 0 10px;">
        <div style="flex:1">
          <div style="font-size:6px;color:#eeeeee">Document Number</div>
          <div style="font-size:8px">FT-1308-3</div>
        </div>
        <div style="flex:1;text-align:center">
          <div style="font-size:6px; color:#eeeeee">Document Title</div>
          <div style="font-size:8px">Validation Protocol</div>
        </div>
        <div style="flex:1;text-align:right">
          <div style="font-size:6px; color:#eeeeee">Revision</div>
          <div style="font-size:8px">1.0</div>
        </div>
      </div>
    </html>
  footerTemplate: |
    <html>
      <div style="width:100%; text-align:Center; border-top: 1pt solid #eeeeee; margin: 0 20px -10px 0; font-size: 8pt; color: #000000">
        CONFIDENTIAL
      </div>
    </html>
  displayHeaderFooter: true
  margin:
    top: "15mm"
    bottom: "15mm"
Document Number: FT-1308-3
---

# Test Case 8: Session and Cookie Management - Session Storage

## Goal

To verify that the Express.js application correctly stores and retrieves session data for authenticated users.

## Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Simulate a user accessing a protected route after successful authentication. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with session and authentication middleware. The user has an active session. |
| 3    | **Test Inputs:** Send an HTTP request to a protected route that requires an authenticated session. |
| 4    | **Test Outputs:** Receive an HTTP response with the appropriate status code, response body, and headers. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The session data should be correctly retrieved and associated with the authenticated user. |
|      | - The response should reflect the protected resource or perform the necessary actions based on the session data. |
|      | - The session data should persist between subsequent requests from the authenticated user. |
