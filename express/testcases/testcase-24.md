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

# Test Case 24: Rate Limiting - Request Throttling

## Goal

To verify that the Express.js application correctly implements rate limiting and throttles requests according to the defined limits.

## Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Send multiple HTTP requests to the specified route within a short time period. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with rate limiting middleware. |
| 3    | **Test Inputs:** Send the HTTP requests to the specified route at a rate that exceeds the defined limits. |
| 4    | **Test Outputs:** Observe the responses of each request to determine if any requests are throttled or rejected due to rate limits. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The application should enforce the defined rate limits and throttle or reject requests that exceed the limits. |
|      | - The response status code for throttled requests should indicate a client error (e.g., 429 Too Many Requests). |
|      | - The response body for throttled requests should contain an error message indicating that the request has been throttled due to rate limits. |
|      | - Subsequent requests that fall within the defined rate limits should be processed without being throttled or rejected. |
