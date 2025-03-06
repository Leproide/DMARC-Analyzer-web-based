# DMARC Analyzer (Web-Based)

A simple web-based utility for parsing and reading DMARC reports, featuring hostname resolution and pass/fail statistics.

## Features
- **File Upload**: Supports drag & drop or manual file selection for `.xml` DMARC reports.
- **Automatic Parsing**: Extracts key DMARC report details, including source IPs, authentication results, and report metadata.
- **Interactive Charts**: Uses `Chart.js` to visualize pass/fail statistics.
- **Expandable Sections**: Displays record details in structured tables.
- **Reverse DNS Lookup**: Fetches hostnames from IPs via a PHP-based resolver.
- **Print Mode**: A toggle for a printer-friendly view.


## Technologies Used
- **HTML**: Structured layout with dynamic elements.
- **CSS**: Dracula-themed styling with a print-friendly mode.
- **JavaScript**: Handles file processing, data parsing, and UI interactions.
- **Chart.js**: Generates pie charts for DMARC statistics.
- **PHP (Backend Resolver)**: Fetches reverse DNS information for IPs.


### Based on:
- **Original project:** [DMARC Aggregate Report](https://github.com/Leproide/DMARC-Aggregate-Report)  
- **Charts powered by:** [Chart.js](https://github.com/chartjs)


## Screenshots

Upload an XML file, enter the domain name (used for the page title), and click **"Generate Report"**.

![Report Example](https://github.com/user-attachments/assets/82c97ae3-533c-46f1-9711-a0a60d1c66f3)  

![Chart Example](https://github.com/user-attachments/assets/9a074181-a1d9-468c-88ca-13572f8519ae)  

Click **"Clear"** to reset the page (a simple reload).  
