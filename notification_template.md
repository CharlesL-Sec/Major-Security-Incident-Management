// Use this as tempalte for sstandardising MSIM notification.
// Features
1. Readable fonts
2. Links to MSI incident
3. Links to MSI task
4. Add assignee name and task reference for subject line.
5. Active link button to MSI and MSI Task


```html
  <p><span style="font-size: 20pt; font-family: verdana, geneva;"><span style="font-size: 12pt;"><strong>${number}</strong> <span style="color: #5b7282;">has been <strong><span style="color: #000000;">proposed</span></strong> as a major security incident by: ${proposed_by}.</span></span><br></span></p>
  <hr style="border: 1px solid #5B7282;">
<p><span style="font-size: 12pt; font-family: verdana, geneva;">You have been identified as a reviewer for a new major security incident candidate <strong><a title="${task_effective_number}" href="/now/msim/major-security-incident/${sys_id}">${task_effective_number}</a> - ${short_description}.</strong></span></p>
<p><span style="font-family: verdana, geneva; font-size: 14pt; color: rgb(91, 114, 130);">About this incident</span></p>
<p><span style="font-family: verdana, geneva;"><span style="font-size: 12pt;"><strong>Justification:</strong> ${justification}<br></span><span style="font-size: 12pt;"><strong>Potential Impact:</strong> ${business_impact}</span></span></p>
<p>&nbsp;</p>
<p><span style="font-size: 12pt; font-family: verdana, geneva;">Please review the details before joining the review call.</span></p>
<p>&nbsp;</p>
<p style="text-align: center;"><span style="font-family: verdana, geneva;"><a style="text-decoration: none; color: white; background: #4F52BD; padding: 8px; border-radius: 5px; border: 1px solid; border-color: #4F52BD; font-size: 16px;" title="Details" href="/now/msim/major-security-incident/${sys_id}">View ${number} in MSIM</a></span></p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><span style="font-size: 12pt; font-family: verdana, geneva;">You will receive a web conference invite shortly to discuss and make a decision on whether to promote this security to a major security incident.</span></p>
<p><span style="font-family: verdana, geneva;"><span style="font-size: 12pt;">Thank you,<br></span><span style="font-size: 12pt;">${proposed_by} (MSIM)</span></span></p>
```
