# Overview

Notes on **USB Hubs** and **cable lengths**.

# References

* [SuperUser Forum Posting](https://superuser.com/questions/64744/maximum-length-of-a-usb-cable)

## YouTube Refences

tbd

## My Other Notes

### Notes in this repository

* [USB2 Techinical Notes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/USB2Notes.md#overview)

### Notes in Other Repositories

* [Hardware Info Repository - USBNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/USBNotes.md#overview)
* [NotesGuidelines](https://github.com/GitLeeRepo/NotesGuidlines/blob/master/NotesGuidelines.md#overview)

# Contents

tbd

# Concepts and Terminology

* **Cable Lengths** -- 5 meters is the maximum USB cable
* **Hubs (Maximums)** -- There is a maximum of 5 hubs serially chained together, with a maximum of 5 meters between each


# Cable Lengths and Extensions Using Hubs

## From SuperUser Forum Posting

* [SuperUser Formu Posting](https://superuser.com/questions/64744/maximum-length-of-a-usb-cable)

5 meters is the maximum USB cable. You can get further by connecting USB hubs serially (maximum of 5 hubs chained this way). You can't just use USB extension cables due to timing issues.

From the USB FAQ:

Q1: How long of a cable can I use to connect my device?
A1: In practice, the USB specification limits the length of a cable between full speed devices to 5 meters (a little under 16 feet 5 inches). For a low speed device the limit is 3 meters (9 feet 10 inches).

Q2: Why can't I use a cable longer than 3 or 5m?
A2: USB's electrical design doesn't allow it. When USB was designed, a decision was made to handle the propagation of electromagnetic fields on USB data lines in a way that limited the maximum length of a USB cable to something in the range of 4m. This method has a number of advantages and, since USB is intended for a desktop environment, the range limitations were deemed acceptable. If you're familiar with transmission line theory and want more detail on this topic, take a look at the USB signals section of the developers FAQ.

Q3: How far away from a PC can I put a USB device?
A3: With the maximum of 5 hubs connected with 5m cables and a 5m cable going to your full speed device, this will give you 30m of cable (see section 7.1.19 for details). With a low speed device, you will be able to get a range up to 27m, depending on how long the device's cable is. With a straightforward cable route, you will probably be able to reach out 25m or so from the PC.

Q4: I need to put a USB device X distance from my PC. What do I do?
A4: If X is less than 25m or so (see previous question), buy a bunch of hubs and connect them serially with 5m cables. If you need to go farther than that, put another PC, or maybe a laptop, out where you need the device to be and network it with the first PC using something that's intended to be a long-range connection, such as Ethernet or RS-485. If you need to use nothing but USB, consider using USB based Ethernet adapters to hook the PCs together.
