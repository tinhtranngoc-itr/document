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

# Test Case 30: Middleware - Error Handling

## Goal

To verify that the Express.js application correctly handles errors and provides appropriate error responses using error handling middleware.

## Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Trigger an error condition in the Express.js application by sending an HTTP request that results in an error. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with error handling middleware. |
| 3    | **Test Inputs:** Send the HTTP request that triggers the error condition. |
| 4    | **Test Outputs:** Receive an HTTP response with the appropriate error status code, error message, and headers. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The application should detect and handle the error condition and return an appropriate error response. |
|      | - The response status code should indicate the error type (e.g., 500 Internal Server Error). |
|      | - The response body should contain an error message indicating the reason for the error and any relevant details. |
|      | - Subsequent requests should not be affected by the error and continue to be processed correctly. |
