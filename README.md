<div align="center">

<img src="assets/logo/stellar-logo.png" alt="STELLAR" width="220" />

# Email Templates

Responsive HTML email templates for STELLAR campaigns.<br />
Built for [Sender](https://www.sender.net/) and compatible with Gmail, Outlook and mobile.

[Website](https://stellarbd.com/) · [Facebook](https://www.facebook.com/stlrbd) · [WhatsApp](https://wa.me/8801810030760)

</div>

<br />

## Templates

<table>
  <tr>
    <td align="center" width="33%">
      <a href="templates/2026-11-hrm-dashboard-update/">
        <img src="templates/2026-11-hrm-dashboard-update/preview.png" alt="HRM Dashboard Update" width="220" />
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

## Structure

```
assets/                      shared logo and icons, used by every template
templates/
  └── YYYY-MM-name/
        ├── index.html       the email
        ├── preview.png      thumbnail for this README
        └── images/          images used only by this email
```

<br />

## Add a new template

1. Copy an existing folder in `templates/` and rename it `YYYY-MM-name` (e.g. `2026-12-year-end-offer`).
2. Edit `index.html`, and put any new images in its `images/` folder.
3. Add a `preview.png`, and add a cell for it to the **Templates** table above.
4. Send yourself a test before using it in a campaign.

<br />

## Image links

Emails need direct image URLs, so use GitHub's raw format:

```
https://raw.githubusercontent.com/MSSohan/HTML-email-template-for-Stellar/main/<path>
```

> [!IMPORTANT]
> Keep this repository **public** and never rename or delete an image a sent email uses. Emails already in inboxes still load it from here.

<br />

## Sending with Sender

Create a campaign → choose the **HTML editor** → paste `index.html` → replace `{{unsubscribe_link}}` with Sender's unsubscribe tag → send a test → send.

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
<sub>© STELLAR · 1005/2/1872 CDA Avenue, East Nasirabad, Chattogram · 01810030762</sub>
</div>
