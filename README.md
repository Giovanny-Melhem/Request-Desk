# Request Desk

**One board for every job, from request to payment.**

Request Desk is a clickable, low-res web prototype for anyone who handles requests from other people, such as a freelancer with clients or an employee with stakeholders. Every request, whether it arrives through a form, a message or in person, becomes one card on one board, so work on standby is not forgotten.

It was made for a design research course (Workbook 5, low-res prototyping), following interviews, observation and a journey map with freelancers and people juggling several workloads.

## Live demo

- Landing page: https://giovanny-melhem.github.io/request-desk/
- V2 (latest): https://giovanny-melhem.github.io/request-desk/v2/
- V0 (first version): https://giovanny-melhem.github.io/request-desk/v0/

## What it does

- **One card per job:** picture, size (small or large), a work status and a separate payment status (amount owed or paid).
- **Piles:** new, in progress, redo, pending and done. Pending means on standby and needs a date to come back to it.
- **Back today strip:** pending jobs that are due today or late come to the top.
- **Client view:** a client sends a request through a form and follows its status. The user accepts it into a pile or declines it.
- **Total owed:** a finished job that is still unpaid keeps counting.
- **Undo delete**, light and dark mode, and typing in both Arabic and English.

### Added in V2

- **Areas:** keep different workloads apart, such as a second job or your own store.
- **Two kinds of area:** Jobs (piles, pending dates, payment) and Information (notes, emails and deadlines).
- **Add card:** one button for both kinds of card, with a prompt to create an area first.
- **Reset and delete per area**, instead of one reset for everything.
- **Clearer status hints** under each pile name.

## Versions

| Version | Folder | Notes |
| --- | --- | --- |
| V0 | `v0/` | First prototype, tested with a freelancer in the first round of user testing. |
| V2 | `v2/` | Built from that feedback and tested with a company employee. |

## Run it locally

No install or build step. Each version is a single self-contained HTML file, so open `v0/index.html` or `v2/index.html` in a browser.

## Data

Everything is saved in your browser's local storage on your own device. Nothing is sent anywhere, and clearing your browser data clears the board.

## Ideas for next

- A QR code per area, so clients reach the right area and send a request to it.
- Optional contact details per area (phone number, address, map location).
- Real client links instead of a same-device request form.
