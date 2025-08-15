# SIR Proposal notification




```html
<p>&nbsp;</p>
<style type="text/css">
  /* General Reset and Body Styles */
  body {
    margin: 0;
    padding: 0;
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
    align-items: center;
    justify-content: center;
  }

  .footer img {
    max-width: 100px;
    /* Adjust as needed */
    height: auto;
    display: flex;
    
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
<div class="email-container">
<div class="header"><img src="logo_banner.pngx" alt="Company Logo">
<p>Major Security Incident Management Notification</p>
</div>
<div class="content"><!-- Example Content Using Flexbox -->
<p><span style="font-size: 20pt; font-family: arial, helvetica, sans-serif;"><span style="font-size: 14pt;"><strong>${number}</strong> <span style="color: #5b7282;">has been <strong><span style="color: #000000;">proposed</span></strong> as a major security incident.</span></span><br></span></p>
<hr style="border: 1px solid #5B7282;">
<p><span style="font-size: 12pt;">You have been identified as a reviewer for a new major security incident candidate <strong><a title="${task_effective_number}" href="/now/msim/major-security-incident/${sys_id}">${task_effective_number}</a> - ${short_description}</strong></span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="font-family: arial, helvetica, sans-serif; font-size: 20pt; color: rgb(91, 114, 130);">About this incident</span></p>
<p><span style="font-size: 12pt;"><strong>Justification:</strong> ${justification}<br></span><span style="font-size: 12pt;"><strong>Potential Impact:</strong> ${business_impact}</span></p>
<p><span style="font-size: 12pt;">You will receive a web conference invite shortly to discuss and make a decision on whether to promote this security to a major security incident.</span></p>
<p><span style="font-size: 12pt;">Thank you,<br></span><span style="font-size: 12pt;">${proposed_by} (MSIM)</span></p>
<p style="text-align: center;"><span style="font-size: 12pt;"><a style="text-decoration: none; color: white; background: rgb(79, 82, 189); padding: 8px; border-radius: 5px; border: 1px solid rgb(79, 82, 189); font-size: 16px;" title="Details" href="/now/msim/major-security-incident/${sys_id}">View ${number} in MSIM</a></span></p>
</div>
<div class="footer"><img src="logo_banner.pngx" alt="Company Logo"></div>
</div>

```

