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

# Test Case 28: Middleware - Request Logging

## Goal

To verify that the Express.js application correctly logs incoming requests using request logging middleware.

## Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Send an HTTP request to the specified route. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with request logging middleware. |
| 3    | **Test Inputs:** Send the desired HTTP request to the specified route. |
| 4    | **Test Outputs:** Verify that the request is logged in the designated log file or logging output. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The Express.js application should log the incoming request with relevant information such as request method, route, timestamp, and client IP address. |
|      | - The logged request should match the sent request in terms of request method, route, headers, and payload. |
|      | - The logged information should be stored in the designated log file or logging output for future reference and analysis. |
