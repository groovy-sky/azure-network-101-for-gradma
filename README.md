# Network Fundamentals in Azure for Eldery People

## Introduction

Following document explains the basics of networking in Azure. It is intended for people who are not familiar with networking and want to learn the basics of networking in Azure. 

For better understanding text is written as if it is addressed to elderly people.

![](/img/cover.svg)

## Table of Contents

* [Module 1: Overview](#module-1)
* [Module 2: Understanding TCP/IP](#module-2)
* [Module 3: Azure VNet Basics](#module-3)

## Module 1: Overview <a name="module-1"></a>

Hello there,

Let's start with a simple analogy: Imagine you want to send a letter to a friend who lives in a different town. You write your letter, put it in an envelope, and drop it in your letterbox. Your local postman collects it and then it goes through various post offices and sorting centres before finally arriving at your friend's letterbox. The process of sending this letter is similar to how a network works in the world of computers and the internet.

When you use your computer or other device (let's call this a 'client') to access a webpage, you're actually sending a request for a document that is stored on another computer (known as a 'server'). The server could be located anywhere around the world.

Your client device is part of a smaller network within your home or office, known as a Local Area Network (LAN). By default, your device doesn't know how to reach the server on its own. Just like our letter needs a postman, our client needs a device known as a 'router' to help deliver its request to the server. 

In our analogy, your letterbox is like the default route your client uses to send its request. The router acts like the postman, collecting your request and deciding the best route to get it to the server. If the server is outside of your LAN (which it usually is), the router forwards your request to another router (or multiple routers) located in a Wide Area Network (WAN).

To continue with our analogy, think of the WAN as the national postal system, a network of various post offices and sorting centres that help deliver your letter to your friend.

The 'traffic' we've been talking about is chunks of data that are sent and received between the server and the client. This traffic is like the contents of the letter you're sending to your friend.

In conclusion, when you access a webpage, you're essentially sending a request (like a letter) via a network of routers (like postmen), which help deliver your request to the right server (your friend) across the internet (the national postal system).

## Module 2: Understanding TCP/IP <a name="module-2"></a>

Your computer is part of a big group of computers, all connected together, kind of like a giant telephone line. This connection is what we call a network.

![](/img/net-explain-00.png)


2. IP Addresses:

Every computer that uses the Internet has a special address, just like your home address. This is called an IP address. When you want to see a webpage, your computer uses this address to find the right place on the Internet.

3. Sending and Receiving Information:

When you want to see a webpage, your computer sends a request, like sending a letter. This request is split into smaller parts, like pieces of a puzzle, to make it easier to send. These pieces are called packets.

4. Routers:

Imagine a router like a traffic policeman, who decides which way cars (or in this case, packets) should go. The router makes sure these packets find the best route to their destination.

5. Servers:

Servers are like the libraries of the Internet. When your computer sends a request to see a webpage, that request is sent to the server that holds that webpage. The server then sends the webpage back to your computer, like a librarian giving you the book you asked for.

6. Protocols:

Protocols are like the rules of the road on the Internet. They make sure all the computers can understand each other and that all the packets go where they're supposed to.

This is a simple explanation of how your computer accesses the Internet. You don't need to remember all the details - just know that it's all about sending and receiving information, just like sending and receiving letters. And all the complicated parts are handled by your computer and the Internet, so you can just sit back and enjoy browsing your favorite websites!

## Used resources

https://www.svgrepo.com/svg/420363/avatar-elderly-grandma

https://www.svgrepo.com/svg/434986/mail-box

https://www.svgrepo.com/svg/283411/mailed-mail