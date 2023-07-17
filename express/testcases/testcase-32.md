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

# Test Case 32: File Upload - Single File

## Goal

To verify that the Express.js application correctly handles file uploads of a single file.

### Protocol

| Step | Description                                                  |
|------|--------------------------------------------------------------|
| 1    | **Test Description:** Send an HTTP request to the specified route with a single file attached for upload. |
| 2    | **Initial Conditions:** The Express.js application is running and properly configured to handle file uploads. |
| 3    | **Test Inputs:** Include a single file as part of the request payload or as a form data attachment. |
| 4    | **Test Outputs:** Verify that the file is successfully uploaded and stored in the designated file storage location. |
| 5    | **Expected Results and Criteria:**                                 |
|      | - The application should handle the file upload request and process the uploaded file appropriately. |
|      | - The response status code should indicate the success of the file upload process (e.g., 200 OK). |
|      | - The uploaded file should be stored in the designated file storage location with the correct file name and format. |
|      | - Subsequent requests should be able to retrieve or access the uploaded file correctly based on the application's file handling logic. |
