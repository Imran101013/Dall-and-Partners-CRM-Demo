# Dall & Partners – Lead Capture, CRM and Client Portal (prototype)

A clickable HTML prototype of the system proposed for Dall & Partners, based on the **free versions** of the WordPress plugins (Fluent Forms, FluentCRM, FluentBooking, Fluent Boards, WP Project Manager, WP Customer Area, Better Messages).

- **Website:** consultation popup, Thank You page with booking calendar, Program Finder (all 25 programs), free guide, blog "next step" box.
- **CRM (staff):** contacts, contact records, follow-up emails, weekly reminder, bookings, availability, sales pipeline (drag and drop), manual tasks list.
- **Client portal:** projects (cases), task lists, calendar, team chat, client dashboard.

Gold notes explain what happens in the live system. Orange notes show tasks staff do by hand on the free plugin versions. Use **Show notes** to hide or show them, and **Reset demo** to start again. Demo data is stored only in the visitor's own browser.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole prototype (HTML, CSS and JavaScript in one file) |
| `process.html` | “How your new system works”: a simple, plain-language guide to the whole process, with links to the demo |
| `How-the-process-works-Dall-and-Partners.pdf` | The same process guide as a PDF, for email |
| `Program-Comparison-2026-Dall-and-Partners.pdf` | The free guide, opened from the guide download page |
| `.nojekyll` | Tells GitHub Pages to publish the files as they are |

## Publish on GitHub Pages

1. Create a new repository on GitHub, for example `dp-prototype` (Public, or Private on a paid plan).
2. Upload all the files above to the repository root (**Add file → Upload files**), then **Commit changes**.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, and click **Save**.
4. After 1–2 minutes the link appears at the top of the Pages screen, for example `https://your-username.github.io/dp-prototype/`.
5. Share that link with the client. The process guide is at `…/dp-prototype/process.html` and is also linked from the prototype’s top bar (“How the process works”).

Links can open a specific screen, for example `index.html#crm-pipeline`, `index.html#site-thankyou` or `index.html#portal-client`.

To update the prototype later, upload the new `index.html` to the same repository; the link stays the same.
