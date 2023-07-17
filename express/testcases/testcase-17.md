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

# Test Case 17: Authorization - Access Granted

## Goal

To verify that the Express.js application correctly grants access to authorized users for protected resources.

### Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Send an HTTP request to a protected route with valid authorization credentials. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with an authentication and authorization system. The user has valid authorization credentials. |
| 3    | **Test Inputs:** Include the necessary authorization credentials in the request headers or payload. |
| 4    | **Test Outputs:** Receive an HTTP response with the appropriate status code, response body, and headers. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The application should grant access to the protected resource for authorized users. |
|      | - The response status code should indicate the success of the access grant (e.g., 200 OK). |
|      | - The response body should contain the expected content or data related to the protected resource. |
|      | - Subsequent requests from the authorized user should also be granted access to the protected resource. |
