---
title: "Kenwood TH-D74 Bluetooth Setup"
date: 2020-04-14T20:42:57-04:00
type: "post"
---

Getting Bluetooth going on the Kenwood TH-D74 was a bit challenging, and information about this radio seems to be spread across multiple videos, blogs, forums, and mailing lists. Here are the steps I took to get Bluetooth working to be able to use the KISS TNC from Windows 10.

1. Download and install the [TH-D74A/E Virtual COM Port Driver](https://www.kenwood.com/i/products/info/amateur/thd74_vcp_e.html) from Kenwood.

2. Turn on Bluetooth on your radio, Menu->930.

3. Set the dataspeed to 1200 bps, Menu->505.

4. Set the data band to B band, Menu->506.

5. Set PC Output(GPS) to Bluetooth, Menu->981.

6. Set the PC Output(APRS) to Bluetooth, Menu->982.

7. Set KISS to Bluetooth, Menu->983.

8. Set DV/DR to Bluetooth, Menu->984.

9. On your computer, make sure Bluetooth is turned on. CLick Add Bluetooth device, choose Bluetooth in the Add a device dialog.

10. On your radio, enter Pairing Mode, Menu->934.

11. Confirm the code on both the computer and the radio, your radio is now paired to the computer.
