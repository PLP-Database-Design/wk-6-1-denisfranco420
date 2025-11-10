🐞 Bug Report

ID: BUG-008
Summary: Top search bar is non-functional — no results appear when searching

Severity/Priority: Major / High
Environment: Chrome 118, Windows 11, Localhost
Affected FR(s): FR-001 (Search Functionality)

Steps to Reproduce:

Open the bookstore homepage.

Type “Mockingbird” in the top search bar.

Press Enter or click the Search button.

Expected Result:

Book list updates to show results for “Mockingbird”.

Actual Result:

Nothing happens. No search request or UI feedback observed.

Attachments:


Notes:

Occurs consistently on desktop and mobile.

May be missing onSubmit or onChange handler in the search component.
![WhatsApp Image 2025-11-10 at 21 55 24](https://github.com/user-attachments/assets/efbe28c8-c344-47f8-b927-522c646607a8)

