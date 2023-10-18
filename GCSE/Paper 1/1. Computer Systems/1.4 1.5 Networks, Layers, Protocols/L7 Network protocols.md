---
title: "GCSE Computer Science - Network Protocols"
format:
  html: 
    default: false
    code-fold: true
  revealjs: 
    default: true
    output-file: document-revealjs.html
    codefocus : true
jupyter: python3
---

## Starter 


![](https://openclipart.org/download/333592/world-map-withgreetings.svg)

If we all speak different languages in different parts of the world, is it possible to communicate with someone who does not speak English, if so how?



## Lesson Objective

By the end of the lesson, you will:

* Be able to explain the use of protocols, including: 
    * HTTP & HTTPS
    * FTP
    * POP, IMAP & SMTP
* Be able to explain the purpose of TCP/IP


## Protocols

A protocol is a set of rules for communicating across a network 

The computers have to use the same rules, why?

![](https://hackmd.io/_uploads/S1lTIrRi-T.png)



## HTTP and HTTPS

HTTP (hypertext transfer protocol) is used to view web pages. Web pages are requested and sent using this protocol

HTTP protocol allows a browser to request files such as text, images, script from a web server, once received they are rendered on the client machine for the user to view

Some websites have an S on the end of the protocol

HTTPS is a secure version of the http protocol, it works in the same way but also encrypts web page data before it is sent, so that no one can read the data

Secure sites would include banking sites or payment pages 



## FTP

FTP is the File Transfer Protocol which is used for sending and receiving files from another computer or server

![](https://hackmd.io/_uploads/Syawr0ibp.png)



## How email works

When we use email we are using a number of protocols, which is shown in the diagram below:

![](https://hackmd.io/_uploads/H1lLOrCi-a.png)



## POP and IMAP

Both of these email protocols FETCH data and attachments from the mail server
You can use either to do the job, but there is a difference
POP (Post office Protocol) will download entire messages to your local device and delete the copy from the server
IMAP (Internet Message Access Protocol) will keep the email on the server even if you download it to a device. This allows you to access the same email on multiple devices. 
POP only supports one mail box but IMAP will handle multiple mail box’s.



## SMTP

SMTP (Simple Mail Transfer Protocol) is used to send emails to servers

![](https://hackmd.io/_uploads/rJgtSAoZT.png)




## TCP/IP Protocol’s

TCP (Transmission Control Protocol)
Breaks up messages sent over the Internet into small chunks called packets
Reassembles the packets at the other end
Detects errors
Resends lost messages
IP protocol
Routes the individual packets



## TCP/IP Protocol

The protocol stack defines four layers in which different protocols operate to pass data packets across a network
The four layers are divisions of network functionality, each carrying out different roles:
Application layer
Transport layer
Network layer
Link layer



## Sending data

The application you are using to send data will determine the correct protocol to use to communicate

![](https://hackmd.io/_uploads/H1R9BCi-T.png) ![](https://hackmd.io/_uploads/Hkzqr0j-T.png)



## Application layer

The network applications you are using operate on the Application layer
The application selects the correct protocol to use depending on which application it is and what you are trying to do
Which application protocol would be selected by:
A browser connecting to a banking website?
An email program used to send a message?
File transfer software used to upload files to a website?
This protocol information is then passed on to the…



## Transport layer

The Transport layer creates the connection between two computers, or ‘hosts’
The two computers agree the communication settings and the size of the packets they will send and receive
Data is then divided up into packets and numbered e.g. 1 of 6
Packets are reassembled by the recipient’s Transport layer
Lost packets are resent
The packets are then passed on to the…



## Network layer

Routers operate on the Network layer
Destination addresses are written on to the packets ready for transmission
Which layer uses the TCP protocol? Why?
Which layer operates using the IP protocol? Why?



The packets are then sent to the… 



## Data link layer

The Link layer is the physical hardware that connects the two hosts such as the NIC and the cabling

![](https://hackmd.io/_uploads/S1DTHCjbT.png)


---

## Arriving at the destination

Data packets move back up the layers:
* The link layer removes the MAC address and passes packets up to the Network layer
* The Network layer removes the IP addresses and passes packets up to the Transport layer
* The Transport layer reassembles the packets and passes the data to the Application layer
* The Application layer uses the correct protocol to correctly display the data, web page or email for the user

![](https://hackmd.io/_uploads/ByQ0BRiba.png)


---

## Exam Question

![](https://hackmd.io/_uploads/SJJ18AiWp.png)

---

## Mark Scheme

![](https://hackmd.io/_uploads/B1uJU0oWT.png)

