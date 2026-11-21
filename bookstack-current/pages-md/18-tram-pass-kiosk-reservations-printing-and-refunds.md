# Tram pass kiosk: reservations, printing, and refunds

## Who this is for

This guide is for homeowners making a tram pass reservation at the office kiosk and office staff who may need to reprint passes or process a refund.

## Start the kiosk

Click the link in the kiosk's bookmark bar. It automatically signs in the kiosk's authorized user.

The link is https://www.sandiahomeowners.org/tram-pass-reservations/USERHASH\_TOKEN

The USERHASH\_TOKEN is set in the .env file. Please refer to the password document for its current value.

## Make a tram pass reservation

1. Enter your address and last name in the kiosk web form.
2. Select the date you want to reserve and the number of tram pass tickets, up to eight.
3. Select **Submit the pass reservations**.
4. Follow the prompt to pay at the kiosk terminal.
5. After payment is complete, the kiosk sends the tram passes to the office printer.

## Reprint a tram pass reservation

If a successful reservation did not print, or needs to be reprinted:

1. Open **Reservations** in the website's administrative area.
2. Select the reservation and press **Print**.

## Refund a tram pass reservation

1. Process the refund in the Square website interface. Refunds cannot be processed on the kiosk or in the website's administrative area.
2. After issuing the refund, open the reservation in the website's administrative area. Remove the refunded number of tram passes. If all passes are being refunded, delete the reservation instead.

Removing the refunded passes from the website makes them available for other homeowners to reserve.

## If the kiosk says it is not connected to Square

Only an authorized website administrator should reconnect the website to Square:

1. Log in to the website's administrative area.
2. Open **Settings**, then select **Square settings**.
3. In the access token section, select **Authorize** or **Refresh**.
4. If Square asks you to log in, sign in and select the blue **Allow** button to authorize the requested permissions.

After reconnecting, return to the kiosk and try again.
