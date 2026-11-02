# Front Office Calendar (DAKboard)

**For office staff and IT support.** The front office calendar is a DAKboard display running on a **Raspberry Pi 3**. Its microSD card was replaced in **September 2026**.

## Manage the display

- [DAKboard control panel](https://dakboard.com/app) — sign in using **sandiahomeowners@gmail.com** to manage the screen and its content.
- [SHHA Flickr photos](https://www.flickr.com/photos/204683280@N03/) — the display pulls its images from this account.

## If it stops working

<table id="bkmrk-problem-what-to-do-s"><thead><tr><th>Problem</th><th>What to do</th></tr></thead><tbody><tr><td>Screen is blank</td><td>Check the monitor's power and HDMI input, the HDMI cable, and the Raspberry Pi's power. Restart the Pi.</td></tr><tr><td>Pi will not start, freezes, or repeatedly stops displaying</td><td>Reflash the microSD card with DAKOS using the steps below. If the card fails again, replace it.</td></tr><tr><td>Display runs, but photos or content are missing</td><td>Check the internet connection and the screen's sources in the DAKboard control panel. For images, check the SHHA Flickr source.</td></tr></tbody></table>

## Reflash the SD card

1. Power off the Raspberry Pi and remove its microSD card. Put the card in a reader connected to another computer.
2. Use [Raspberry Pi Imager](https://www.raspberrypi.com/software/) and follow the official [Download and Install DAKOS instructions](https://dakboard.freshdesk.com/support/solutions/articles/35000125880-raspberry-pi-download-and-install-dakos). Write **DAKboard OS (DAKOS)** to the card; writing erases the selected card.
3. Reinsert the card, power on, and follow the on-screen setup to reconnect to the office network and the existing SHHA DAKboard account. Select the existing front office screen.

Still stuck? Contact [IT Help](mailto:ithelp@sandiahomeowners.org). Return to the [Staff guide](https://wiki.sandiahomeowners.org/books/shha-it-help-guide/page/staff) for other office procedures.
