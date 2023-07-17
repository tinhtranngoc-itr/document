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

# Test Case 34: Error Handling - Route Not Found

## Goal

To verify that the Express.js application correctly handles requests to non-existent routes and provides appropriate error responses.

## Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Send an HTTP request to a route that does not exist in the Express.js application. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured. |
| 3    | **Test Inputs:** Send the HTTP request to the non-existent route. |
| 4    | **Test Outputs:** Receive an HTTP response with the appropriate error status code, error message, and headers. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The application should detect the non-existent route and return an appropriate error response. |
|      | - The response status code should indicate a client error (e.g., 404 Not Found). |
|      | - The response body should contain an error message indicating that the requested route does not exist. |
|      | - Subsequent requests to valid routes should be processed correctly without any impact from the non-existent route request. |
