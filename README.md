<div align="center">

<img src="readme-banner.png" alt="STELLAR Email Templates" width="100%" />

<br /><br />

Responsive HTML email templates for STELLAR campaigns.<br />
Built for [Sender](https://www.sender.net/) and compatible with Gmail, Outlook and mobile.

<br />

<a href="https://stellarbd.com/"><img src="https://img.shields.io/badge/Website-stellarbd.com-1F6FEB?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Website" /></a>
<a href="https://www.facebook.com/stlrbd"><img src="https://img.shields.io/badge/Facebook-stlrbd-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook" /></a>
<a href="https://wa.me/8801810030760"><img src="https://img.shields.io/badge/WhatsApp-Chat-128C7E?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>

</div>

<br />

## Templates

<table>
  <tr>
    <td align="center" width="33%">
      <a href="stellar-hrm-dashboard-update-html-email.html">
        <img src="stellar-hrm-dashboard-update.png" alt="HRM Dashboard Update" width="220" />
      </a>
      <br /><b>HRM Dashboard Update</b>
      <br /><sub>Product update · Nov 2026</sub>
    </td>
    <td align="center" width="33%">
      <sub><i>Next template</i></sub>
    </td>
    <td align="center" width="33%">
      <sub><i>Next template</i></sub>
    </td>
  </tr>
</table>

<br />

## Files

| File | Purpose |
|:--|:--|
| `STELLAR Logo name beside.png` | Logo, shared by all templates |
| `readme-banner.png`, `readme-footer.png` | Gradient header and footer for this README |
| `stellar-hrm-dashboard-update-html-email.html` | HRM Dashboard Update email |
| `stellar-hrm-dashboard-update.png` | Hero image for that email |

<br />

## Add a new template

Each template is a pair of files with the same name:

```
<template-name>-html-email.html     the email
<template-name>.png                 its hero image (also the preview above)
```

1. Copy `stellar-hrm-dashboard-update-html-email.html` and rename it, e.g. `stellar-year-end-offer-html-email.html`.
2. Upload its hero image with the matching name, e.g. `stellar-year-end-offer.png`.
3. In the new HTML, update the content, links and the hero image URL.
4. Add a cell for it to the **Templates** table above, and a row to **Files**.
5. Send yourself a test before using it in a campaign.

<br />

## Image links

Emails need direct image URLs, so use GitHub's raw format:

```
https://raw.githubusercontent.com/MSSohan/HTML-email-template-for-Stellar/main/<file-name>
```

Spaces in file names must be written as `%20`, e.g. `STELLAR%20Logo%20name%20beside.png`. Social icons load from [Icons8](https://icons8.com/).

> [!IMPORTANT]
> Keep this repository **public** and never rename or delete an image a sent email uses. Emails already in inboxes still load it from here.

<br />

## Sending with Sender

Create a campaign → choose the **HTML editor** → paste the template's HTML → replace `{{unsubscribe_link}}` with Sender's unsubscribe tag → send a test → send.

<br />

## Brand

| | Colour | Use |
|:-:|:--|:--|
| ![](https://placehold.co/16x16/0B1F44/0B1F44.png) | `#0B1F44` | Headings, footer |
| ![](https://placehold.co/16x16/1F6FEB/1F6FEB.png) | `#1F6FEB` | Primary button |
| ![](https://placehold.co/16x16/128C7E/128C7E.png) | `#128C7E` | WhatsApp button |
| ![](https://placehold.co/16x16/1877F2/1877F2.png) | `#1877F2` | Facebook button |
| ![](https://placehold.co/16x16/EEF2F8/EEF2F8.png) | `#EEF2F8` | Background |

**Font:** Segoe UI, Roboto, Helvetica, Arial, sans-serif

<br />

<div align="center">
<img src="readme-footer.png" alt="stellarbd.com · Chattogram, Bangladesh · 01810030762" width="100%" />
<br />
<sub>© STELLAR. All Rights Reserved.</sub>
</div>
