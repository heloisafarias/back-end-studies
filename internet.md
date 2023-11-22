# How does the Internet works?
## In this chapter we're going to learn more about how the Internet we know works.
### You can find a dictionary with some concepts and keywords [HERE](/dictionary.md)
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


* IP - Internet Protocol is responsible for routing the packets for the correct destination. It's an unique identifier that is attributed to a device, example: 192.168.1.1

* TCP - Transmission Control Protocol is responsible for assuring those packets are trustable and are in the correct order.

* DNS - Domain Name System. This is how the website will be called, example: github.com.

DNS is going to translate the name of the website you are accessing into an IP Address.

How this is going to work:

![How DNS works](https://github.com/heloisafarias/back-end-studies/assets/86490011/e21b420d-749a-47fd-8658-9327d390c86b)

* HTTP e HTTPS - Hypertext Transfer Protocol or Hypertext Transfer Protocol Secure.

HTTPS is responsible for making the information exchanging between the client (Web browser, like Chrome) and the server (the Website you are navegating).
When you enter a website your browser send a HTTP request asking the webpage you are accessing. So, if everything is ok, the server will return it into a HTTP response, in this case a HTTPS response, which is responsible for encrypting the data.

![how HTTPS works](https://github.com/heloisafarias/back-end-studies/assets/86490011/8e3a1116-0ad7-43a0-9e7a-efe0cbc0fb26)


