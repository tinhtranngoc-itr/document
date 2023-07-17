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
# Test Case 5: Templating Engine Integration - Render HTML View

## Goal

To verify that the Express.js application correctly integrates and renders HTML views using the specified templating engine.

## Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Define a route that renders an HTML view using the specified templating engine. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured with the required templating engine and view templates. |
| 3    | **Test Inputs:** Send an HTTP GET request to the specified route. |
| 4    | **Test Outputs:** Receive an HTTP response with the appropriate status code, response body containing the rendered HTML view, and headers. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The HTML view should be rendered correctly using the specified templating engine. |
|      | - The response status code should be 200 (OK).                      |
|      | - The response body should contain the expected HTML content based on the view template. |
|      | - The response headers should include any necessary headers based on the application's configuration. |
