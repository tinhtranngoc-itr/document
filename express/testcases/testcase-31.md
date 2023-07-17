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

# Test Case 31: Middleware - Authorization

## Goal

To verify that the Express.js application correctly handles user authorization using authorization middleware.

## Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Send an HTTP request to a protected route with valid authentication credentials but without the necessary authorization. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with authorization middleware. |
| 3    | **Test Inputs:** Include valid authentication credentials in the request headers or payload. |
| 4    | **Test Outputs:** Receive an HTTP response with the appropriate error status code, error message, and headers. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The application should verify the authentication credentials and check for the necessary authorization to access the protected resource. |
|      | - If the user does not have the required authorization, the response status code should indicate a client error (e.g., 403 Forbidden). |
|      | - The response body should contain an error message indicating that the user does not have the necessary authorization. |
|      | - Subsequent requests from the authorized user should be granted access to the protected resource. |

