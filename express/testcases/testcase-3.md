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

# Test Case 3: Middleware Integration - Custom Middleware

## Goal

To verify that the Express.js application correctly integrates and executes custom middleware functions in the defined middleware stack.

### Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Define and register a custom middleware function in the Express.js application. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured. |
| 3    | **Test Inputs:** Send an HTTP request to a specified route that triggers the execution of the custom middleware function. |
| 4    | **Test Outputs:** Receive an HTTP response with the appropriate status code, response body, and headers. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The custom middleware function should be executed as part of the middleware stack. |
|      | - The response should reflect any modifications or actions performed by the custom middleware. |
|      | - The subsequent middleware functions and the route handler should execute correctly. |
