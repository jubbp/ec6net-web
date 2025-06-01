---
title: APRS Messaging
subtitle: Text Messaging without Telcos
layout: page
show_sidebar: false
menubar: docs_menu
toc: true
---


## No Store and Forward

It is important to note that APRS messaging (in its purest form, without internet access) does not do store and forward and than the station you are wishing to contact must be in range of you or a digipeater. If you station is not listening for you message, it will not recieve it. You should know if the station does recieve your message as they should send your back an ACK packet.

## APRS Path

The choice of PATH when sending APRS packets is an important consideration. Your path selection can limit your ability to reach stations further from you.

The suggested PATH is WIDE1-1,WIDE2-2

WIDE1-1 allows for infill digipeaters (which only respond to WIDE1 paths) to pass your message on to a WIDE2 repeater which you msy not be able to reach

WIDE2-2 allows a chain of 2 digipeaters pass on your message. 

So using the PATH WIDE1-1,WIDE2-2 can send your message through a chain of up to 3 digipeaters. After 3 digipeats it will die.

In South West Western Australia, this path will get you through most of the major digipeaters and allow you to send APRS messages to almost any station from Perth to Margaret River and east to Katanning.

The choice of this path is working on the assumption that intermet access is not available and you would like to maximise your coverage without using the internet

