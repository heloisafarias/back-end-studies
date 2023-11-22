# How does the Internet works?
## In this chapter we're going to learn more about how the Internet we know works.
### You can find a dictionary with some concepts and keywords [in the Dictionary](/dictionary.md)
The Internet is a network of networks. But what is a network?
Network is a group of devices grouped together. The connection between them is called Internet.

The way the Internet connects the devices is through protocols. These protocols define how data is exchanged between devices in a secure and reliable way.

The core of the Internet is a network of routers interconnected, that are responsible for the traffic between differents devices and systems.


![imagem](https://github.com/heloisafarias/back-end-studies/assets/86490011/f5c26ba7-2fa5-400b-ac9d-5e1673eb6215)


In this image we can see how data is send to another device. But how are these packets being sent correctly?

Do you remember protocols? They are responsible for sending the data to the correct destination/device. 

## Internet Protocols

Protocols are very important in data exchange. They assure that the data sent will be received by the correct destination in a secure way.
A protocol is a group of patterns that defines how the data transfer will be made between devices.

## IP, TCP, DNS
* IP - Internet Protocol is responsible for routing the packets for the correct destination. It's an unique identifier that is attributed to a device, example: 192.168.1.1

* TCP - Transmission Control Protocol is responsible for assuring those packets are trustable and are in the correct order.


* DNS - Domain Name System. This is how the website will be called, example: github.com.

DNS is going to translate the name of the website you are accessing into an IP Address.

How this is going to work:

![How DNS works](https://github.com/heloisafarias/back-end-studies/assets/86490011/e21b420d-749a-47fd-8658-9327d390c86b)

You can see some important concepts of TCP/IP [in the Dictionary](/dictionary.md)


## HTTP E HTTPS


* HTTP e HTTPS - Hypertext Transfer Protocol or Hypertext Transfer Protocol Secure.

HTTPS is responsible for making the information exchanging between the client (Web browser, like Chrome) and the server (the Website you are navegating).
When you enter a website your browser send a HTTP request asking the webpage you are accessing. So, if everything is ok, the server will return it into a HTTP response, in this case a HTTPS response, which is responsible for encrypting the data.

![how HTTPS works](https://github.com/heloisafarias/back-end-studies/assets/86490011/8e3a1116-0ad7-43a0-9e7a-efe0cbc0fb26)

## SSL/TLS

* SSL -> Secure Socket Layer;
* TLS -> Transport Layer Secure;

This two are secure protocols used for a safe communication at the Internet.
They assure the data you are exchanging through the Internet are safe, applying rules so everything is confidential.

These are some keywords that you have know to study this protocols:
* Certirficates -> The certificates in SSL/TLS are used to establish confiability between the client and the server. It contains information about the identity of the server and are certificated by an authority (ex: Microsoft) to verify it and assure it's safe.
* Handshake -> The Handshake is the definition of what the server and the client do while "talking", so they can negotiate the encryption of the information and other secure parameters they are exchanging.
* Encryptation ->  The connection being estabilished, the data is encrypted using an encription algorithm, and can be exchanged in a safe way between both client and server.

  
![How the handshake will work](https://github.com/heloisafarias/back-end-studies/assets/86490011/076f0c37-00e5-4b48-9aad-4f99a2954ff8)

## Hosting a website

A website is hosted on a server. It's like a house in the Internet where it's gonna live.
This "place" is some company hardware server. Companies sell different types of server to host your website.
You can divide it with a hundred other people, buy how much of space you want this house to have or even buy your own server.
It's gonna depend on the purpose of the website you are building and how many data you're gonna exchange.

![webhostin](https://github.com/heloisafarias/back-end-studies/assets/86490011/6b493a5a-3ab7-486d-ac58-2c3cf54489d9)



