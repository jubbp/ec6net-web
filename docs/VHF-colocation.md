---
title: VHF Colocation
subtitle: Locating 2 VHF radios on one site
layout: page
show_sidebar: false
menubar: docs_menu
toc: false
---

How can we colocate 2 VHF radios at our home QTH to allow use of APRS or packet stations in
close proximity to our home VHF station.

The following is a collection of notes on the subject. Its not a finished document at the moment.

## Operating a Digipeater near a voice repeater

To operate an APRS digipeater near a voice repeater, you'll need to use a duplexer to separate the APRS and
voice signals on the same antenna. This allows both the voice repeater and the digipeater to transmit
and receive on their respective frequencies without interference.

Here's a more detailed explanation:

### Frequency Separation

The two-meter voice repeater should ideally be in the upper 146 or 147 MHz range. Avoid frequencies in
the 145 MHz segment as they are too close to the APRS frequency and can cause interference.

### Duplexer Selection

A duplexer is a filter that separates the transmit and receive frequencies. Two types of duplexers are often recommended:

- Res-lok Series (e.g., Sinclair Q2220, Q2222, Q2330): These are known for their square construction design and reliability.
- Notch Filters: These resemble UHF duplexers but are actually VHF notch filters. Make sure they cover the necessary frequency range.

### Example

Let's say the voice repeater is on 147.150 MHz transmit and 147.750 MHz receive. You would then use a suitable
duplexer to allow the APRS digipeater (typically on 144.39 MHz) to transmit on the same antenna without interfering with
the voice repeater.

#### Installation

The duplexer is installed between the radio and the antenna, separating the APRS and voice signals.

##### Testing and Fine-Tuning

After installation, it's important to test the system to ensure proper performance. You might need to adjust the duplexer settings or antenna placement to optimize signal quality.

### References

[aprs.org digiduplexing.pdf](https://www.aprs.org/txt/digiduplexing.pdf)

[VHF duplexer on Aliexpress](https://www.aliexpress.com/item/1005005284394150.html)

[Ham Radio DX video - Cheap Duplexer](https://www.youtube.com/watch?v=I_Trk9OKG38&t=797s)

[VHF Repeater duplexer Alibaba](https://www.alibaba.com/product-detail/136-174MHz-VHF-0-6MHz-Duplexer_1600083924879.html?spm=a2700.shop_plgr.41413.35.30e37121rBZMJx)

[Calibrate a Duplexer with a NanoVNA](https://www.youtube.com/watch?v=TbEK4v_3Xuo)

[Diplexers in your vehicle video](https://www.youtube.com/watch?v=CJvJBDEDGiQ)