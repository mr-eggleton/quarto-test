---
title: "GCSE Computer Science - Networking"
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

## {auto-animate=true}

``` mermaid
mindmap
  )"Networking"(
::icon(fa fa-network-wired) 
    ))1: Types of Network((
    ))2: Network Topologies((
    ))3: Network Performance((
    ))4: Network Hardware((
    ::icon(fa fa-network-wired)    
    ))5: Client Server((
    ))6: The Internet((
    ))7:Network Protocols((
    ```

## {auto-animate=true}

``` mermaid
mindmap
  )"Networking"(
::icon(fa fa-network-wired) 
    ))1: Types of Network((
    ))2: Network Topologies((
    ))3: Network Performance((
        Mediums
            Wired
                Copper
                    Ethernet 
                    ::icon(fa fa-ethernet)
                Fiber
            Wireless
            ::icon(fa fa-wifi)
                ☹️ Negative Effects
                    Interference - Microwave etc.
                    Steel frame buildings                           
                    Weather  
                Frequency 
                    2.4Gz
                        😃 Range & Coverage
                        ☹️ Interference
                        ☹️ 3 non-overlapping channels
                    5GHz
                        😃 23 non-overlapping channels
                        ☹️ Walls
        Measurements
            Bandwidth
            Latency

    ))4: Network Hardware((
    ::icon(fa fa-network-wired)    
    ))5: Client Server((
    ))6: The Internet((
    ))7:Network Protocols((
    ```

## {auto-animate=true}

``` mermaid
mindmap
  )"Networking"(
::icon(fa fa-network-wired) 
    ))1: Types of Network((
        LAN
        WAN
    ))2: Network Topologies((
        Star
        Mesh
    ))3: Network Performance((
        Mediums
            Wired
                Copper
                    Ethernet 
                    ::icon(fa fa-ethernet)
                Fiber
            Wireless
            ::icon(fa fa-wifi)
                ☹️ Negative Effects
                    Interference - Microwave etc.
                    Steel frame buildings                           
                    Weather  
                Frequency 
                    2.4Gz
                        😃 Range & Coverage
                        ☹️ Interference
                        ☹️ 3 non-overlapping channels
                    5GHz
                        😃 23 non-overlapping channels
                        ☹️ Walls
        Measurements
            Bandwidth
            Latency
    ))4: Network Hardware((
    ::icon(fa fa-network-wired)    
        Network Interface Card
        ::icon(fa fa-ethernet)
            MAC Address
            Connects device to others on network
        Hub
        ::icon(fa fa-ethernet)
            Connects devices together / Center of a star
            ☹️ All messages down all wires
                Data collisions, Slow
            ☹️ Old tech
        Switch
        ::icon(fa fa-ethernet)
            Connects devices together / Center of a star
            Sends data down the wire it needs to
            to the MAC address of device 
        Router
            Transfer data between networks
        Network Cabling
            Ethernet 
                CAT5
                CAT6
            ::icon(fa fa-ethernet)
            Fibre optic  
        Others
            Wireless access points
            Powerline kits
            Gateway
            Bridge 
    ))5: Client Server((
        Client Server Network
            Server
            ::icon(fa fa-server)
                Computer and software to provide Resources
                Share resources to all machines on network
                    File Storage
                    Databases
                    Printers
                    Calculations
                    Games
                    Application Servers
            Client
                On end users Computer
                Software requests resources / work on the Server
                easy to set up
                a client thats turned off will take the resources with them
            Virtual Network
                Software that runs on physical network hardware dividing it up
                Virtual Local Area Network
                    Staff and Student networks have different resource access
                    Improves security by separating computers
                Virtual Private Network
                    Encrypts traffic so only the computers inside the VPN can access messages and resources
                    Over Internet
                    Cheaper than own WAN 
        Peer to Peer network
            Resources are distributed on End users computers
    ))6: The Internet((
        World Wide Web
        ISP
        URL
        IP Address
        DNS
        Cloud Services
    ))7:Network Protocols((
        Application layer
            http & https
            FTP
            Email
                POP
                IMAP
                SMTP
        Transport layer
            TCP (Transmission Control Protocol)
                Breaks up messages sent over the Internet into small chunks called packets
                Reassembles the packets at the other end
                Detects errors
                Resends lost messages
        Network layer
            IP protocol
                Routes the individual packets
        Link Layer
            Ethernet
            Fibre Optic
            Wifi
            3/4/5G
```