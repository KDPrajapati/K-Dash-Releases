# K-Dash

**See your business clearly, straight from the books you already keep.**

K-Dash is a 64-bit Windows app for business owners who keep their accounts in Tally.
It reads your books from files you export from Tally (paid plans can also read Tally
directly) and answers the questions you would otherwise dig out by hand: who owes you
money and for how long, what is running low, and what your products earn.

**It never changes your accounts.** Everything K-Dash asks Tally for is a read. Reading
a large book can slow Tally down, so save your work in Tally before you sync.

## Who it is for

Any business that keeps its books in Tally: manufacturers, distributors, wholesalers
and traders. You can teach K-Dash how your customers and products are named; it
remembers, and you can see and undo what it has learned under **What this app has
learned**.

## What it does

- **Who owes you.** Customer by customer: what each owes, and how old their oldest
  unpaid bill is.
- **What is running low.** Stock that needs attention, worked out from your own sales.
- **What your products earn.** Margins by product, from the costs in your own book.
  Where a product has no cost, the main profit figures say "not costed".
- **On paid plans:** money coming in and going out, and staff logins where you pick
  the screens each person opens and whether they can change anything.
- **Careful with deletes.** A restore point is taken before a delete. Old automatic
  backups are cleared after the number of days you set; a backup file you rename
  yourself is never touched.

## Your data stays on your PC

Your book and your licence key are kept on your computer. K-Dash reads Tally only when
you press a button that asks it to; it never reads on its own. K-Dash's own internet
features, such as checking for a new version, stay off until you turn them on under
**Settings → Internet access**. WhatsApp and web-link buttons open your browser and are
not covered by that switch.

## Download and install

Each public update is published under [Releases](../../releases). Download the
`K-Dash-Setup` file from the newest one and run it. If K-Dash is already installed, run
the new installer over the top: your book, your backups and everything you have taught
the app are kept. **Do not uninstall first.**

The installer is not code-signed yet, so Windows may warn about an unrecognised
publisher (choose **More info → Run anyway**), and your browser may ask you to keep the
file.

**Check your download.** Each release has a signed `manifest.json` listing the
installer's SHA-256. If you download the installer yourself, compare its SHA-256 with
the one in `manifest.json`. When K-Dash updates itself, it refuses any download that
does not match the signed file.

## Plans and licences

Update 9 and earlier open on the free plan without a key; later updates ask for a
licence key the first time they open. Paid screens do not appear on the free plan;
**Settings → Plan & licence** lists what each plan adds. Enter your key there, then
close and reopen K-Dash.

To get a licence, e-mail **krupeshdprajapati@gmail.com**.

## What is in this repository

Built installers and their signed manifests. The source code is private.
