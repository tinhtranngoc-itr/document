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

# Test Case 22: Caching - Response Caching

## Goal

To verify that the Express.js application correctly handles response caching and improves performance for repeated requests.

### Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Send multiple HTTP requests to the same route with identical request parameters. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with caching middleware. |
| 3    | **Test Inputs:** Send the HTTP requests with the same route and request parameters. |
| 4    | **Test Outputs:** Observe the response headers of each request to determine if the response is being served from cache or generated anew. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - For the first request, the application should generate the response and include appropriate caching headers. |
|      | - For subsequent identical requests, the application should serve the response from cache without regenerating it. |
|      | - The response headers should indicate that the response is being served from cache (e.g., "Cache-Control: public, max-age=3600"). |
|      | - The application should update the cached response when necessary (e.g., when the data being cached is modified). |
