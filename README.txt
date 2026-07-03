Invoice Generator App v8 - C/O fixed payment + frozen buttons

Upload all files in this folder to your GitHub Pages repository root:
- index.html
- manifest.json
- sw.js
- icon.svg
- README.txt

What's new in v8:
- If the BD/RT/BT/AB category contains C/O, the app treats the saved rate as a fixed change-over payment.
- For C/O rows, Amount = Rate. It does not multiply KM by rate.
- Add C/O rates in Settings, for example BD C/O = 515, RT C/O = 515, or general C/O = 515.
- New Invoice, Preview, and Save buttons are centred and fixed in the top app bar on the Invoice screen.
- Main navigation remains fixed at the top: Invoice, All Invoices, Settings.

After upload, open your app with ?v=8 once, for example:
https://invoice.apsprofencing.com.au/?v=8

Then go to Settings -> Update App once if needed.


Version 9: Fixed the frozen header/actions so they stay in place during horizontal as well as vertical scrolling.


v10: Keeps only the top button/header area fixed. Invoice content scrolls normally; wide load/misc tables scroll inside their own boxes.
