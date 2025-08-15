---
layout: post
title: Data Structures and Algorithm Visualization Toolkit Project
subtitle: Personal Project / Study Guide
comments: false
mathjax: false
author: Alex V.
---

{: .box-success}
In this project, I developed a toolkit that implements and visualizes the most fundamental data structures and algorithms – specifically arrays, multidimensional arrays, bubble sort, merge sort, and binary search trees (search, delete, insert). My goal was to use Python and Jupyter Notebooks to create a comprehensive toolkit that can be used as a reference and as a study guide for data structures and algorithms.


## Data Structure and Algorithm Visualization Project

Project report:  <a href="#" onclick="downloadPdf1(event)" download="My_Project_Report.pdf">Download Project Report PDF (Link)</a>
<body>

    <script>
        function downloadPdf1(event) {
            // Prevent the default link behavior for the pdf (force downloading, prevent opening)
            if (event) {
                event.preventDefault();
            }

            // File path
            const pdfUrl = 'https://alvg2.github.io/datastructureproject/pdfs/Project_Report.pdf'; 

            // Desired filename for download
            const suggestedFileName = 'My_Project_Report.pdf'; 

            // Create a temporary anchor element
            const link = document.createElement('a');
            link.href = pdfUrl;
            link.download = suggestedFileName; // Set the download attribute

            // Append to the body (not strictly necessary for click() but good practice)
            document.body.appendChild(link);

            // Programmatically click the link to trigger the download
            link.click();

            // Clean up: remove the temporary link
            document.body.removeChild(link);
        }
    </script>
</body>
- to open enter the following twice: v23GhQkp#cBf!@P!

Project printout:  <a href="#" onclick="downloadPdf2(event)" download="Project_Printout.pdf">Download Project Printout PDF (Link)</a>
<body>

    <script>
        function downloadPdf2(event) {
            // Prevent the default link behavior for the pdf (force downloading, prevent opening)
            if (event) {
                event.preventDefault();
            }

            // File path
            const pdfUrl = 'https://alvg2.github.io/datastructureproject/pdfs/Project_Printout.pdf'; 

            // Desired filename for download
            const suggestedFileName = 'My_Project_Printout.pdf'; 

            // Create a temporary anchor element
            const link = document.createElement('a');
            link.href = pdfUrl;
            link.download = suggestedFileName; // Set the download attribute

            // Append to the body (not strictly necessary for click() but good practice)
            document.body.appendChild(link);

            // Programmatically click the link to trigger the download
            link.click();

            // Clean up: remove the temporary link
            document.body.removeChild(link);
        }
    </script>
</body>
- to open enter the following twice: qcLFUS6p&t9d$tEV

Also, you can find these links in my Project Website: [Project Website Link](https://alvg2.github.io/datastructureproject/)



