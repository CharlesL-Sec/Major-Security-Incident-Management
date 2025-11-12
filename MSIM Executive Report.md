MSIM Executive Report HTML

```html
<style type="text/css">
  /* General Reset and Body Styles */
  body {
    margin: 0;
    padding: 0;
    background-color: lightgray;
    padding: 1rem;
    font-family: Lato, Arial, sans-serif;
    -webkit-text-size-adjust: none;
    /* Prevent font size adjustments on mobile */
    background-color: #f4f4f4;
    /* Optional: Light background for the entire email */
  }

  /* Responsive Container */
  .email-container {
    width: 100%;
    max-width: 670px;
    /* Original table width */
    margin: 20px auto;
    /* Center the container */
    border-collapse: collapse;
    overflow: hidden;
    /* Ensures rounded corners work correctly */
    border-radius: 10px;
    /* Optional: Rounded corners for the whole email */
    box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    /* Optional: Subtle shadow for depth */
  }

  /* Header Section */
  .header {
    background-color: rgb(255, 102, 0);
    /* Orange background */
    color: rgb(236, 240, 241);
    /* Light text color */
    text-align: center;
    padding: 20px;
  }

  .header img {
    max-width: 200px;
    /* Adjust as needed */
    height: auto;
    display: block;
    margin: 0 auto 10px;
  }

  .header p {
    margin: 0;
    font-size: 1.2em;
  }

  /* Content Section */
  .content {
    background-color: #ffffff;
    padding: 20px;
  }

  /* Example Flexbox Layout for Content */
  .content-row {
    display: flex;
    flex-wrap: wrap;
    /* Allows items to wrap on smaller screens */
    margin-bottom: 15px;
    /* Spacing between rows */
  }

  .content-col {
    flex: 1;
    /* Each column takes up equal space */
    padding: 10px;
    min-width: 200px;
    /* Minimum width for each column */
    box-sizing: border-box;
    /* Include padding in width calculation */
  }

  /* Footer Section */
  .footer {
    background-color: rgb(255, 102, 0);
    /* Orange background */
    color: rgb(236, 240, 241);
    /* Light text color */
    text-align: center;
    padding: 20px;
    font-size: 0.8em;
  }

  .footer img {
    max-width: 100px;
    /* Adjust as needed */
    height: auto;
    display: block;
    margin: 0 auto 10px;
  }

  /* Utility Classes (from your original CSS) */
  .btn a {
    text-decoration: none;
  }

  .btn.inverse a {
    color: #fff;
  }

  #requestapprove a {
    color: #fff !important;
  }

  /* Mobile Link Styling */
  .mobile-link a,
  .mobile-link span {
    text-decoration: none !important;
    color: inherit !important;
    border: none !important;
  }
</style>
<div>
<p style="font-size: 20pt; color: #ff6600; font-family: arial, helvetica, sans-serif; margin: 2rem; text-align: center;">EJ MSIM Executive Status Report</p>
<hr style="border: 2px solid #c55a11;">
<div class="content-row">
<div class="content-col">
<p><span style="font-size: 10pt;"><strong>MSI Task Number:&nbsp;</strong>${number}</span></p>
<p><span style="font-size: 10pt;"><strong>Updated by:</strong> ${sys_updated_by}</span></p>
<p><span style="font-size: 10pt;"><strong>Incident Start:</strong>&nbsp; ${sys_created_on}</span></p>
</div>
<div id="colunm two" class="content-col" style="color: orange;">
<p><span style="font-size: 10pt;"><strong>Code name</strong>: ${code_name}</span></p>
<p><span style="font-size: 10pt;"><strong>Priority</strong>: High</span></p>
<p><span style="font-size: 10pt;"><strong>Category</strong>: ${category}</span></p>
</div>
</div>
<div class="content-row">
<div class="content-col">
<p style="font-size: 10pt;"><strong>Description:&nbsp;</strong></p>
<p>${short_description}</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
</div>
</div>
</div>

```
