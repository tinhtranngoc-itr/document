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

# Express.js<br/>Validation Protocol

## Revision History

| Version | Approved by | Revision Date | Description of Version | Author |
| :-----: | ----------- | ------------- | ---------------------- | ------ |
|   1.0   |             | 03/09/2023    | Initial version        | Tinh Tran       |
|         |             |               |                        |        |
|         |             |               |                        |        |

<!-- pagebreak -->

## I. Introduction

### A. Goal

The goal of this validation protocol is to ensure that the software solution using Express.js meets the specified requirements and functions as intended. It aims to verify the accuracy, reliability, and performance of the software through a series of test cases.

### B. Scope

This validation protocol covers the testing of the software solution using Express.js. It includes the execution of the identified test cases to validate the functional and non-functional aspects of the software.

### C. Responsibility

The responsibility for executing the validation activities outlined in this protocol lies with the designated validation team or individuals. They are responsible for following the specified test procedures, documenting the test results, and reporting any issues or observations during the validation process.

### D. Validation steps

The validation steps consist of the execution of the following test cases:

1. Test Case: Routing and Request Handling - Valid Request
2. Test Case: Routing and Request Handling - Invalid Request
3. Test Case: Middleware Integration - Custom Middleware
4. Test Case: Middleware Integration - Third-Party Middleware
5. Test Case: Templating Engine Integration - Render HTML View
6. Test Case: Templating Engine Integration - Template Inheritance
7. Test Case: Error Handling - Server Error Response
8. Test Case: Error Handling - Client Error Response
9. Test Case: Session and Cookie Management - Session Creation
10. Test Case: Session and Cookie Management - Session Storage
11. Test Case: Database Integration - Create Record
12. Test Case: Database Integration - Read Record
13. Test Case: Database Integration - Update Record
14. Test Case: Database Integration - Delete Record
15. Test Case: Input Validation - Valid Input
16. Test Case: Input Validation - Invalid Input
17. Test Case: Authentication - User Login
18. Test Case: Authentication - User Logout
19. Test Case: Authorization - Access Control
20. Test Case: Encryption - Secure Communication
21. Test Case: Error Handling - Error Logging
22. Test Case: Performance - Response Time
23. Test Case: Performance - Concurrent Requests
24. Test Case: Usability - API Documentation
25. Test Case: Usability - Error Messages
26. Test Case: Integration with External API - GET Request
27. Test Case: Integration with External API - POST Request
28. Test Case: Integration with External API - Response Validation
29. Test Case: Configuration Settings - Valid Configuration
30. Test Case: Configuration Settings - Invalid Configuration
31. Test Case: Scalability - Load Testing
32. Test Case: Security - Input Sanitization
33. Test Case: Security - SQL Injection Prevention
34. Test Case: Cross-Site Scripting (XSS) Prevention
35. Test Case: Cross-Site Request Forgery (CSRF) Protection

<!-- pagebreak -->

## II. Validation protocol

1. Test Case 1: See preference: [testcase-1.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EXzORNZpnjxNiioSgfsw4PQBNQTT0eguz39NARObWMiGNA?e=h5njBm)
2. Test Case 2: See preference: [testcase-2.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Eflxmg9SCvpBlOT-zxV0ejUBofnDp0owOcGUjkx59PgqMA?e=1b16JC)
3. Test Case 3: See preference: [testcase-3.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EWNn6jhCkQ1Iq_q_WaE_MD0BngkyfTgI6GmdbddDfolccw?e=pM7tv5)
4. Test Case 4: See preference: [testcase-4.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EZs3rN17txBMk3FltGSeKycBSJmAWIR-ghFOXaKe08Vp5Q?e=DFhwjA)
5. Test Case 5: See preference: [testcase-5.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EcayPkOhi6xPquXbUgb1ScMBkW8AwWQxiVSvnIdWfSoMRg?e=rYr3Q4)
6. Test Case 6: See preference: [testcase-6.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EcHemqyIfQpMmsbk2lhdVHUB3YmyIQXAom6Zx4mm4AAc5g?e=Bpe1Uv)
7. Test Case 7: See preference: [testcase-7.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ERtqzyTWz4NOhfpVa8J69UoBNlUGXW1oGv7QtwcieYjC0A?e=ypq70d)
8. Test Case 8: See preference: [testcase-8.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EdFZ-3EfaS1NmHzG4pjLdWEB-mygrkb220XAwOXRsv7WFA?e=Byin4n)
9. Test Case 9: See preference: [testcase-9.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EU7m3FPNdUFLjCNccSBVwn0B-tWnEfmtK94zOmotXUiAuw?e=JmZgqG)
10. Test Case 10: See preference: [testcase-10.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Ec9-IUpFseRBlo6aMOWZiloBh7lrrZiB7uTszXOhiC4oAg?e=ddDWqd)
11. Test Case 11: See preference: [testcase-11.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EbBjBLGV6QhHuxLpxNgSQXoBOPIerXHWAffT3o4oeLpZrg?e=OwWu8M)
12. Test Case 12: See preference: [testcase-12.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Ec5ucpaFygRMo2TPMDA0JZ8BnnTrzp6OWAAXqK49r5yBeQ?e=reYwVH)
13. Test Case 13: See preference: [testcase-13.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EV32ZxJ5PfFJiMl1NannjUwB_P420-Sut_vUu198BXdgTg?e=vFW7Yc)
14. Test Case 14: See preference: [testcase-14.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EcQz05k1qbxDkcZG2Gm6OYwB9s5wb2ldf0XSmlyCZ5ki2Q?e=E7hdge)
15. Test Case 15: See preference: [testcase-15.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ESDXOmUNjxFFkDUJiaDnsXYBaDHfeAEkYABmUYaZF-qToA?e=9GL37O)
16. Test Case 16: See preference: [testcase-16.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ESUyRiw1IwtJiw5JGMsQGuMB9fp0vxaUP7Cs68EatvhjrQ?e=cUvncG)
17. Test Case 17: See preference: [testcase-17.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Edgufcqn7vFJm-upqRlSz9EBkmV4zqabkqI4oTiSCls_IA?e=Y6C0Be)
18. Test Case 18: See preference: [testcase-18.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Ed5OVW3Jy9FDnw7EIo-y40MBHuy2hXQGd1BGojE0K-Wd0g?e=7kZ6CY)
19. Test Case 19: See preference: [testcase-19.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ER_6IguylilElCgHo4eY4rsBnqFjtKA6g1j_9gNrYF9ccQ?e=7LvAmC)
20. Test Case 20: See preference: [testcase-20.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EZLOCDrh7_tBqcEGnH9bhNsBhqZPMStKHuxsGZ38TwQykQ?e=cFZbLH)
21. Test Case 21: See preference: [testcase-21.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Ee1h2ZLUCptIrOJ-K_oq8HEB7kC9G4Uh4d40ulKQ5w1mxw?e=xcWRwd)
22. Test Case 22: See preference: [testcase-22.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EbSlIcsBj0VNhUUHMOzrFAcBaKkhQBdiHlcH2t3fyfd8Rw?e=h327cH)
23. Test Case 23: See preference: [testcase-23.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EdNPUWv3TgtKng_sej6rsE4BDt6Ud2lBmyeugJjMGURcXQ?e=Q7F8iq)
24. Test Case 24: See preference: [testcase-24.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EXXL6d-lEwlEjPxxv8yb5YwBRadCZgukVPssp46JuwUvoQ?e=8QZBC1)
25. Test Case 25: See preference: [testcase-25.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EZLMoXwm01ZKlQt47AhBsCEBpKNCnimx-9urKj5N8gXklw?e=59QZPA)
26. Test Case 26: See preference: [testcase-26.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EVTuYIiRt31HlKqaMKCxVWEBWYQ6SrypZVSW5KVpIacZng?e=Ghe7Vh)
27. Test Case 27: See preference: [testcase-27.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EUzfsTrHDD1AjrWR7WsKxCQBnYc36adr1C99estNHJP4VQ?e=4Md4rB)
28. Test Case 28: See preference: [testcase-28.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ERNjhGTX1XlHicXMvHUKuPoB3g8XLx8FC5UsKIJ11WhCxg?e=NmDFDh)
29. Test Case 29: See preference: [testcase-29.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EcsddajnbzlGrbYEyX88ttMBtmHoSytEz2kz26M-nI2yZA?e=07qAvb)
30. Test Case 30: See preference: [testcase-30.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EQOPck_UQe5CiutxIKHRyVUB-MKzFEgYg5F9VMazFSigug?e=MhNJ18)
31. Test Case 31: See preference: [testcase-31.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EYBoBIbVaGlGl_gVyakGi_kBxztpeNqJQFe5bpDOx56Ufg?e=VuVyKD)
32. Test Case 32: See preference: [testcase-32.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EVaDz0pQ0nVGu46pQZv8fT4BLLmUpMdT9FW2iNG4YUUySw?e=djY5dc)
33. Test Case 33: See preference: [testcase-33.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ER9dWJG_P7dGqXPU6g6AW4UBDa3oAhYlShapExUe092V4A?e=IsNKzs)
34. Test Case 34: See preference: [testcase-34.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EW1uJLXCk61DiWtC-eq1B7cBRFdTasBeAMFo3NY2SsUeCw?e=4966ke)
35. Test Case 35: See preference: [testcase-35.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EX6rBC_Q59ZOoYqbyTeU68QB7tOj_iSO0Rgr05yJwzFyUA?e=UW5e2I)

<!-- pagebreak -->

## III. Activities supporting validation and after validation

### A. Training of personel

### B. Revalidation

Mongo JS is reviewed each year.
