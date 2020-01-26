# Overview

Notes on USB 2.0 technology from a general view point.  For the more technical, as in when programming microprocessors for USB 2/0 refer to the [USB2TechNotesAndSpecifications](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/USB2TechNotesAndSpecifications.md#overview) document.  For more of a consumer view of **USB in general** refer to the [USBNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/USBNotes.md#overview) in the **Hardware Info Repository**

# References

tbd

## YouTube Refences

* [USB 101](https://www.youtube.com/watch?v=5S6ZPmtPzRA) -- Silicon Labs presentation -- short but good overview

## My Other Notes

### Notes in this repository

* [USB2TechNotesAndSpecifications](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/USB2TechNotesAndSpecifications.md#overview) document
* [ElectronicNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/ElectronicsNotes.md#overview)
* [PICNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/PICNotes.md#overview)
* [PICArchitectAndAssemblyNotes](https://github.com/GitLeeRepo/ElectronicsNotes/blob/master/PICArchitectAndAssemblyNotes.md#overview)

### Notes in Other Repositories

* [USBNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/USBNotes.md#overview)
* [Hardware Info Repository - USBNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/USBNotes.md#overview)
* [NotesGuidelines](https://github.com/GitLeeRepo/NotesGuidlines/blob/master/NotesGuidelines.md#overview)

# Contents

tbd

# Concepts and Terminology

* **Bulk Transfer Type** -- includes **Mass Storage device** and **Communication Device Class (CDC)**.  It has **high throughput**, but **low priority**.  It provides **guaranteed delivery with error checking**.
* **Cable Lengths** -- **5 meters** is the maximum USB cable
* **Descriptor** -- a **structure** in the **firmware** that contains **USB Information**, such as what **type of device** and what **interfaces it supports**.
* **Device** -- also called **peripheral** is the **slave device** that connects to the **host**.
* **Enumeration** -- the **handshaking** process **between device and host**. The **beep** you hear in **Windows** is the begining of the **enumeration process**
* **Frame** -- **time based grouping** with **fixed timing**. It is the **basis of all USB communication**.  It is made up of **multiple packets**.
* **Host** -- the organizer and **master** of all **traffic on the bus**
* **Hub** -- **expands the number of devices** that can attach to a **host**, along with acting as a **repeater** extending the distance to the device. There is a **maximum of 5 hubs** serially chained together, with a **maximum of 5 meters between each**
* **In transfer** -- moves from the **device to the host**
* **Interrupt Transfer Type** -- **low throughput** with **high priority** and **guaranteed latency**.  It includes **Human Interface Devices (HID)** such as **mouse** and **keyboard**.
* **Isochronous Transfer Type** -- used for **audio** and **video**.  It provides **no guarantee of delivery** with **high throughput**.  Used when **dropped packets** are **not critical**.
* **OTG** -- **On the Go** -- allows **USB devices**, such as tablets or smartphones, to **act as a host**, allowing those devices to **switch back and forth** between the roles of **host and device**.
* **Out transfer** -- moves from the **host to the device**
* **Packet** -- a bundle of **data** organized into a **group for transmission**.
* **Root Hub** -- the **base hub** on the **host** that all **devices** and **additional hubs** attach to.
* **USB** -- **Universal Serial Bus**.

# General USB

Refer to:

* [Hardware Info Repository - USBNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/USBNotes.md#overview)

## USB Hubs and Cable Lengths

Refer to:

* [Hardware Info Repository - USBNotes](https://github.com/GitLeeRepo/HardwareInfoNotes/blob/master/USBNotes.md#overview)

Brief Info:

* **Cable Lengths** -- **5 meters** is the maximum USB cable
* **Hubs (Maximums)** -- There is a **maximum of 5 hubs** serially chained together, with a maximum of **5 meters between each**

