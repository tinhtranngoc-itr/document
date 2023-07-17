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

1. Test Case 1: See preference: [testcase-1.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EarB9IWKVEpFqfjXH88VwikBEHx7_vWfGZgAnfBdg8w9wA?e=9yhee2)
2. Test Case 2: See preference: [testcase-2.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Eb5h7e_MFMhLvw4GwZvwSnoBkk4936rl-ens8hXmgrXTkw?e=bgJK2H)
3. Test Case 3: See preference: [testcase-3.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ER-Ds2xmyyVIlifwH8wkZA8BgULai5c8HB287pBhzVQbfw?e=5UGRYq)
4. Test Case 4: See preference: [testcase-4.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EaJxvrrzgelNhScAXVPMVhwBzse-ekqyMj7hwCB6ws4T-g?e=EBxB3r)
5. Test Case 5: See preference: [testcase-5.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EYmJAhw1YK5LkoLjeTp3ZscBSd7J4v2TPi-8BBbxhQxt_w?e=oOuGkP)
6. Test Case 6: See preference: [testcase-6.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EUnckncLO1BCspF0xhdbJf4BEeFYCqZaYQ16vLI7rofdnQ?e=xTohj3)
7. Test Case 7: See preference: [testcase-7.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ESV1cBktS85MojOfSnPbEjsBXEKEsMFECZfu2LIR3Opbjw?e=LmGRe7)
8. Test Case 8: See preference: [testcase-8.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EY5x7ZxVsyZPuFFDylgxUl0BS3hCEm40MPipFd8dFvolMQ?e=LqsNDc)
9. Test Case 9: See preference: [testcase-9.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ETkXSysTS0RJg0398a2HGdoBGYAXdQKdV49VWrr6AlZPwA?e=S6e70H)
10. Test Case 10: See preference: [testcase-10.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Ebstup_TF-JHqzY_1cJ5QjYBrXABxhXxz5VQa1eOnPVutw?e=TYOCt5)
11. Test Case 11: See preference: [testcase-11.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/Ee0kvr6IDKhNmJj8bsj2Uw0B8ukqSg_Cvi77ze-rjuvNvw?e=mcW5i8)
12. Test Case 12: See preference: [testcase-12.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EVhKZfuq33lPlPu7YtTrn7QBTayoDh-Xue5-zQ-1HZyIQQ?e=Xv70NU)
13. Test Case 13: See preference: [testcase-13.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EfftUqxjMR9Ps4MW_muTpccB5y2vx4Fyy4rt2iHY6LqQbQ?e=t4PW2W)
14. Test Case 14: See preference: [testcase-14.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EfWGHVqNIv1IpbeA85rEK64BF9IGIqGPiYwPU9Ltxtf0eA?e=5GcvOu)
15. Test Case 15: See preference: [testcase-15.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EVyYjhIGnzRMg6CwKtlcfjABnhLYnBbhyfkabrs6DRzbeQ?e=fshTTS)
16. Test Case 16: See preference: [testcase-16.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ETmWqgElRLlBrz4HDH2eEqMBfJ-__cUepAVuAQVtR-dJEQ?e=Qvcb9O)
17. Test Case 17: See preference: [testcase-17.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ETJHgviXgEVLlSKbskHWh1kBIxXbn8B9-HHvqtI3H980WQ?e=fDZJVW)
18. Test Case 18: See preference: [testcase-18.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EaqLhQAGIXxJidExcNnSIicBltbbvAHZviycyXOUyxbYeQ?e=p1EIrZ)
19. Test Case 19: See preference: [testcase-19.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EaEVLIfYRDpDiThY86I9BMgB1dPCgX5Ox2Nfg4Kp7IZptQ?e=TkLC3o)
20. Test Case 20: See preference: [testcase-20.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EbA37Bz0-bFAgeqV4RPwqOIBumQKTQmlyQvMSA--TNuJMw?e=m3yi52)
21. Test Case 21: See preference: [testcase-21.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EXypHeIub2FMnELab3BvdVoB9vAQQiQcOuq5Eq3qyNX5-A?e=HUrO6k)
22. Test Case 22: See preference: [testcase-22.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EbknbukBTGpKpn8EV0xiAugB6aJxBgGx_7GDcZIKVgQyDw?e=pjrqDa)
23. Test Case 23: See preference: [testcase-23.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EVgytpj1p6dLnWjA9GL4olMB2-3XY76dPYowExH_FAzeUg?e=ZoGgAN)
24. Test Case 24: See preference: [testcase-24.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EQEq6SM3DWlLoQGyYXZoUZQBM25I_n_a1jFo8YGF1F79hQ?e=1CSRQr)
25. Test Case 25: See preference: [testcase-25.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ETwyAoM5-99Ki0Hm9XYRoFcBoSAGRiOg9bxrk4c_ZDJ0cw?e=aAe2cu)
26. Test Case 26: See preference: [testcase-26.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EdzLpCIwkcdOggq_FrUcMCIBbjOZnAJqafHiGYbWH4cnKA?e=1RgyMg)
27. Test Case 27: See preference: [testcase-27.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EaufYzzDb6RFkYAUWMs7JKoBE0TgG2KNienhBsJsMpwIBA?e=UfPRrW)
28. Test Case 28: See preference: [testcase-28.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EZI43Djum8hBo1e--88GS9QBk_K6IG1vOAgwLFdftbRwUg?e=kmDB9m)
29. Test Case 29: See preference: [testcase-29.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EVHqPcpI9w1Br2MnSHibpZwBkO7csbwtHCD_HdXEFAxz_A?e=JlJP0V)
30. Test Case 30: See preference: [testcase-30.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/ERfFIvCehYlOhWf_4cG7OGcBOIajrWQeBSreGD4nYl9Kcg?e=SVZDkP)
31. Test Case 31: See preference: [testcase-31.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EYAFaozEP9RMnb5tQHPMyU4BkVZzaNMaULcc7GpGAwafUQ?e=QbfFHO)
32. Test Case 32: See preference: [testcase-32.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EXhL-mKqSjFPvCyehedu_7oBawAgNrEo6rM5GoBAWPIK9Q?e=qDUgxi)
33. Test Case 33: See preference: [testcase-33.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EXD-9lz8AH5OjkPWdhDwD0oB3tW-OCiH9RwRWx_bwKQt_w?e=hSKgBi)
34. Test Case 34: See preference: [testcase-34.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EYNweDsM3FlOl3cSIHkc6NAB4hWZVDX2-dLWah2JHaPmtQ?e=Uw54cA)
35. Test Case 35: See preference: [testcase-35.md](https://itrvn.sharepoint.com/:t:/s/CNGTYCPHNITRVN-BackendTeam/EZv6lsSVEuhDozs1L5oW4AYBmsZGADR3YNJFcyZvEklOKA?e=oSkqjk)

<!-- pagebreak -->

## III. Activities supporting validation and after validation

### A. Training of personel

### B. Revalidation

Mongo JS is reviewed each year.
