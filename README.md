### Review of IPTV Interactive Services and Implementation of a Typical Service
<div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/AppleTV.png" width="1000"></div>

An interactive service is one that enables user to receive a transmission of data specially created for the recipient, or upon request, whether or not as part of a program, which is selected by or on behalf of the recipient.
Interactive services present users with various capabilities. The service provider can combine these capabilities with other services to create two-way communications with the client. The application is implemented to be used on a platform, however it has the least confluence with the main processes of its platform and independently runs and interacts with the user.


### Commercial Innovation Strategies and Implementation Patterns in Interactive Services
 1. Adding supplemental features to existing services
 2. New interaction-based services
 3. Side-mode integration of existing services
 4. Personalization & thematic specialization of existing services
 5. Appending content-oriented interactions to existing services



## Interactive IPTV Applications
<div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/IPTV.png" width="500"></div>

As the transition from all things analog to digital continues, iTV is becoming more and more prevalent. Thanks to increased bandwidth in new networking infrastructure and the great carrying capacity of the compressed digital signal, interactive content can be offered to more and more householders. iTV describes the phenomenon whereby users are enable to actively engage with content on their TV screens. iTV adds an extra layer of functionality to IPTV beyond on-demand and linear programming services.


It can provide viewers with access to further information, communication applications, and the facility to respond to interactive programming. Deployment of interactive applications involves the transition from one-way to two-way communications and passive to active viewing and viewer control. Applications and programming are transmitted to viewers’ set-top boxes and viewers can interact by using a navigational device such as a remote control or a wireless keyboard. Information sent by viewers is directed from the set-top box to a return path to the host’s network server. Deployment of interactive applications has occurred because a digital signal, which is compressed and transmitted at higher speeds in binary code, can carry more interactive content and numerous channels. iTV is distributed to people’s homes by terrestrial, cable, IPTV, and satellite television providers, each of these groups are consistently battling for a place in the viewers’ homes. All of these providers encourage viewers to subscribe to their pay TV, broadband, and telephone services and usually, they offer a variety of packages, which are designed for different audience types and the different budgets of their audiences.
In addition to allowing subscribers to watch linear video programming, IPTV brings Web-like interactivity to the traditional TV viewing experience. It allows service providers to differentiate their offerings from traditional television services. For consumers it allows them to view hundreds of channels, simultaneously record TV material, and access a range of interactive TV services including

### Types of Commercial Interactive Services
##### <a href="#EPG"> 1. Electronic Programming Guide</a>
##### <a href="#VoD"> 2. VoD</a>
##### <a href="#Browsing"> 3. Browsing</a>
##### <a href="#E-mail"> 4. E-mail</a>
##### <a href="#CallerID"> 5. Caller ID</a>
##### <a href="#Advertising"> 6. Advertising</a>
##### <a href="#GoD"> 7. GoD</a>
##### <a href="#EAS"> 8. EAS</a>
##### <a href="#DVR"> 9. DVR</a>
##### <a href="#WGP"> 10. Walled Garden Portal</a> 
##### <a href="#IM"> 11. Instant Messaging</a>
##### <a href="#Commerce"> 12. IPTV-Commerce</a>
##### <a href="#Social"> 13. Social Networking</a>
##### <a href="#Localized"> 14. Localized Video Content</a>
##### <a href="#Parental"> 15. Parental Control</a>
##### <a href="#Personalized"> 16. Personalized Channels</a>
##### <a href="#Weather"> 17. Weather Forcast</a>

Interactive television will provide genuinely useful applications that enhance the overall user experience of IPTV. Interactive services must be seen as part of the overall infrastructure of delivering television – not just a bolt on.
To get the right interactive services to meet consumer demands will require experimentation. Content providers, broadcasters and network owners need to develop, trial, refine and roll-out interactive services. A lot has been learnt over the past ten years about interactive TV. This knowledge can help inform the design of interactive services for IPTV.


<div id="EPG" align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/EPG.png" width="850"></div>



### 1. Electronic Programming Guide(EPG)

Since IPTV brings into the home many more channels and services, people need a way of navigating the myriad of choices. An application that does this is typically referred to as an electronic program guide. An EPG, also known as intelligent program guides (IPG), is an interface application that allows IPTV subscribers to preview, select, and connect to various types of IP and interactive TV services. The EPG application is generally a standard part of an IPTV service offering and is commonly used to navigate through a growing number of channels and sources of video content available to subscribers. An EPG presents IPTV subscribers with a menu of available IPTV channels in HTML format and a remote control is typically used to navigate this menu. Owing to the two-way nature of IPTV networks, it is possible to include several full days of programming information for every channel and detailed descriptions of every program within each channel. In addition, subscribers are able to search by genre, program title, channel, and even by time. Once a channel is selected, the video content is downloaded over the broadband network for immediate viewing. The EPG application is usually displayed on the TV screen in tabular or grid format. This type of design is generally easy to read and understand. It is however possible to change the look and feel of the EPG interface to meet the branding requirements of different IPTV service providers. The communication process between the client EPG application running on the IP set-top box and the server application uses standard Internet protocols. If the IPTV transmission network is using multicasting, then the program descriptions retrieved by the IP set-top box also contain port numbers and related multicast IP addresses.

##### Introduction to IPTV EPGs 

Also known as an event service guide, an IPTV EPG displays program lineup and episode information for current and future broadcast programming choices. It displays the current channel contents in a window, and allows IPTV subscribers to select a particular broadcast channel. Subscribers use the arrow keys on their remote controls to highlight and select various options. The functions of a standard IPTV EPG can include the following:
Displaying weekly schedules of IPTV multicast channels. Note that the channels accessible on the weekly channel are defined by the end-user access rights.
Automatic video recording.
Alerting subscribers about the arrival of new e-mail.
Reminding viewers when a selected program (or a program covering a selected topic) is about to be shown.
Restricting access to TV channels that are deemed inappropriate.
Allowing subscribers to find programs with a particular theme on a specified time or date.
Controlling disk storage devices in IP set-top boxes.
Previewing particular programs and personalizing TV viewing.
Some advanced IPTV systems even allow subscribers to program the EPG to make it look the way they want it.
A picture-in-guide is a variation of the standard IPTV EPG application that displays a selection of multicast channels within a small window (stamp like images) on the TV screen. The end user is able to use the arrows on their remote control to move from one window to the next. Each time a window is selected, the IPTVCD plays the sound associated with the particular channel. In addition to sound, the set-top will also display channel information including title, beginning, and ending times. By simply pressing the OK or Enter button on their remote control, the window extends to the full length and width of the television screen, the end user can sit back and watch the channel in comfort. From a network engineering perspective, multiple streams are required to support the provision of a picture-in-guide interactive TV application. This is problematic for service providers that operate networks with low bandwidth capacities. Note the delivery of this interactive IPTV application also requires picture-in-guide functionality to be built into the encoders at the IPTV data center.

##### IPTV EPG End-to-End

Network Architecture figure below describes the building blocks that comprise an end-to-end IPTV EPG solution:
The underlying technology platform has three major components, namely, a metadata generator, an EPG application server located at the IPTV data center, and a client EPG application resident on the IPTVCD. We explore these technical components in the following subsections.
Metadata Generator: The EPG needs schedule data to allow the viewer receive information about IPTV broadcast and on-demand services. The technical and industry term for this data is metadata. The metadata generator is at the heart of an end-to-end IPTV EPG system and allows IPTV service providers to acquire, edit, generate, and play out EPG schedule data over the network. IPTV metadata defines data about data and is typically formatted in XML. It combines video content information from both the content provider and network operator. The types of metadata provided by an IPTV system can include some of the following items:
List of channels available for the various tiered packages
IPTV channel name
IPTV channel description
IPTV channel logo
IPTV channel provider
IPTV channel provider’s Web site
Program title
Program start and finish times
Program language options
Detailed description of program contents
Parental control details and rating standards
Content aspect ratios
An indicator of whether captions are available or not
A description of any embedded advertisements
Compression techniques used on both audio and video content
Prices and access conditions for different items of IPTV content
Scheduled distribution time for delivery across the IP broadband network
Description of protocols and mechanism used to deliver the content
Caching details
Preview duration for IP-VoD assets
Recording rights
Applicability of content to particular types of IPTVCDs
Viewing profiles of IPTV end-users


##### End-to-end IPTV EPG system: Application Server 

The metadata generator interfaces with the EPG server to deliver program information to the EPG client application in a suitable format. The application server consists of software programs, a HTTP server, and a centralized database that contains the event data of all the broadcast programs on offer. It has four main functions:
(1) Formatting—The channel listing are generally formatted as Web pages.
(2) Authorization—The server in conjunction with the conditional access and digital rights management system authorizes access to particular channels.
(3) Provision of IP multicast addresses—The EPG server provides IP multicast addresses which are used by the router to stream the IP video channel across the core and access IP networks.
(4) Caching—The IPTV EPG server also provides caching functionality, which speeds up the EPG load time for end-users.
Client EPG Application The level of functionality provided by the EPG client
application can include some or all of the following features:
Allows end users to customize list of favorite multicast channels and on-demand titles.
Allows end users to change the look and feel of the screen layout.
Provides end users with an efficient mechanism of navigating through the various IPTV services and channels that are on offer from the network operator.


##### Launching an EPG via an IPTVCD connected to an IP

The steps involved in launching an EPG application are illustrated in the figure above and explained in following sections:
Step 1—The EPG key is pressed and the client application processes the
command.
Step 2—Launching of an EPG over an IPTV network utilizes a browser based client-server networking model. Thus, the next step in the process involves the establishment of a network connection between the EPG browser application and backend server.
Step 3—The command is received in the form of IP packets, authenticated, and a Web page is generated by the server. The Web page will contain channel information requested by the end user. This information will either be cached at the IPTV EPG server or requested from the metadata generator.
Step 4—The IPTV EPG server sends the results of the end-user request to the client EPG browser application.
Step 5—Results are received, rendered, and the EPG page is layed out on the TV display for use by the end user.

The EPG network architecture described above relies on the ability of the network and backend servers to respond immediately to EPG instructions. On some occasions IPTV end users may experience delays due to congestion or other issues that slow down the processing of EPG requests. Where this occurs on a regular basis, service providers have an option of using an architecture that involves processing the EPG locally on the IPTVCD. Under this approach the basic EPG application normally resides in the IPTVCD’s storage system and accesses current meta-data from the IP network. Local storage of the EPG application speeds up broadband network response times for the end-user because it launches and operates immediately once the IPTVCD is powered on.


<div id="VoD"></div>


### 2. IP Based Video on Demand (VoD)

IPTV is often provided in conjunction with VoD. As the name implies VoD is a service that allows subscribers to select and download video content over an IP network. The content typically includes a library of films, music videos, and recorded television programs. The deployment of a VoD system falls into two broad categories:

Downloadable—the VoD content is delivered to the IP set-top box and the content is viewed once the downloading is finished.
Streaming—The IPTV set-top box receives the content via an IP stream.
A VoD system is the “holy grail” of viewing TV and enables an individual subscriber located in geographically dispersed locations to demand a program or movie when and where they want it.
The selection of a VoD title by an IPTV end user is relatively easy and typically comprises the following five steps:

The subscriber selects a VoD title from the interactive TV application.
The IPTVCD accepts the command and sends this instruction to the headend or data center.
The conditional access system is checked to verify that the subscriber is authorized to view the particular VoD title.
Once authorization is complete, a unicast video stream is forwarded to the regional office and onward to the IPTVCD.
The IP stream is controlled by the subscriber.

In addition to a high capacity two-way broadband network, the deployment of IP-VoD services also requires a number of other logical and physical technology blocks:

IP-VoD streaming server(s)
IP-VoD transport protocols
An Interactive IP-VoD client application

We explore these technology blocks in the following subsections.
IP-VoD Streaming Servers

In addition to the various processes that are executed in IPTV data centers, namely, encoding, multiplexing, and modulation, a number of high capacity computer servers are also installed to allow the delivery of IP-VoD services to various types of IPTVCDs. The main function of these VoD streaming servers is to retrieve and deliver on demand video content to a distribution network.
IP VoD servers are built using standard off-the-shelf computer and electronic components. Lots of processing power, fast input/output (I/O) systems, and large amounts of storage space are the main hardware characteristics of VoD streaming servers. Fortunately, for IPTV service providers the prices for these components continue to fall, while their capacities are continuing to rise. A video server typically includes redundant components such as power supplies, hot swappable hard drives and multiple CPUs. It acquires VoD assets from a number of content sources and is typically able to handle a range of different types of compression formats including MPEG-2, H.264/AVC, and VC-1. A Gigabit Ethernet output provides connectivity to the access network.
A large database of video movies and program assets resides on the server. The server receives requests for a particular content asset from VoD capable IPTVCDs, identifies the item, and streams the requested item to the IPTVCD.
The size and capabilities of the video server varies from supplier to supplier. A cluster of IP-VoD servers incorporate operating systems and application software that optimize the process of streaming video assets and simplify the day-to-day operations of the overall system. The operating systems used by VoD servers vary between vendors. The application software typically performs a number of critical functions.


##### Setting up a VoD stream

Management of Digital Streams: The setup, teardown, and control of VoD streaming sessions is a core function of the VoD server software.
A graphical illustration showing the steps associated with establishing an IP-VoD stream between a client IP set-top box and a backend VoD server is shown in the figure above and explained in the following sections.
Start communication with the CA System—On receipt of a request from the IP set-top box, the server software communicates with the CA system to determine if the IPTV subscriber has been authorized to view the requested IP VoD asset.
Identify appropriate IP-VoD Server—Once authorization has been verified, the software identifies a suitable VoD server cluster to fulfill the request. The location of this server or cluster of servers will depend on the IP subnet of the requesting set-top box.
Send encryption keys across network—Once the server cluster has been allocated, the backend software or the CA system sends a decryption key to the IP set-top box to facilitate decryption of the IP VoD content.
Send IP parameters—IP transport protocol parameters and the IP address of the VoD server is also sent to the IP set-top box.
IP VoD streaming commences—Bandwidth is allocated and streaming of the IP VoD asset commences. The IP set-top box uses a protocol called Real-Time Streaming Protocol (RTSP) to manage the flow of the stream.

While the stream is live on the network, it is the responsibility of the server software to ensure that if a fault occurs that the fail over system is activated and the stream continues without interruption.
Updating Digital Content: A VoD software infrastructure has to have the capability to automatically manage the updating of video content. Relying on a manual system to keep VoD content libraries up to date is problematic. 
The backoffice software ensures that all the digital assets included in the VoD library are current. This is achieved by automatically loading files from the content reception system into the VoD cluster of servers.
Replication Management: The backoffice software manages the replication of digital assets across a distributed networking infrastructure. In the event that new content is made available, it is the responsibility of this software to ensure that the asset is propagated to edge and cache servers around the network.
Management of Metadata: A centralized database is used to store the various attributes or metadata that are associated with each of the digital assets. Metadata is generally formatted as an XML file and provides descriptive data about each video asset. Metadata is typically used to search and browse VoD content. The types of metadata associated with a standard movie include
Movie producers name
Description
Date when the movie was created
Movie summary
Parental rating
Run time of the movie
Actor and director details
Genre
Licensing details
Royalty details
The backoffice software is responsible for ensuring the integrity of this metadata. Industry groups such as CableLabs have defined a standard for VoD metadata.
Search Capabilities: The indexing capabilities of video server software allow IPTV end users to carry out searches for digital assets on the backend IP-VoD servers.
Managing Access of IP-VoD Digital Assets: The server software provides an external interface to the service provider’s back office components — the conditional access, digital rights management, and billing systems. Inputs from this interface are used to control and manage access to the digital VoD assets.
Interfacing with IPTVCDs: The back-office software is also responsible for interfacing and communicating information about VoD assets that are available for purchase to the VoD client software application installed on various types of IPTVCDs.

##### IP VoD Transport Protocols

IP VoD servers typically use the Real-time Transport Protocol (RTP) and Real-time Control Protocol (RTCP) to stream video data to an IPTVCD. The Real-Time Streaming Protocol is subsequently used to control these streams. The following sections give a brief overview of these three protocols when used in an IPTV infrastructure.

Overview of RTP and RTCP
As the name suggests RTP is a native part of the IP suite of communication protocols. It was published as a standard by the ITU-T and has been specifically designed to carry signals for a wide range of realtime applications.
In addition to IPTV there are several other applications that use the RTP protocol ranging from video conferencing to VoIP. Applications that run RTP usually do so on top of the UDP and IP protocol layers. This is because RTP provides appropriate QoS mechanisms and is able to recover from problems that go undetected by UDP.
RTCP or the control part of RTP monitors the quality of real-time IPTV services. Its main function is to work with protocols such as UDP to provide feedback information to the IPTV data center systems about the quality of data delivery and reception. The types of feedback information ranges from how many IPTV packets were lost while traversing the network to delays in the delivery of IPTV packets.

RTSP Overview 
Real-Time Streaming Protocol is an application level protocol belonging to the IP communication model that enables IPTVCDs to establish and control the flow of IPTV streams. The specification for RTSP was published in 1998 and can be found in RFC 2326. It allows IPTVCDs to issue VCR style commands to an IPTV streaming server. The figure below shows how these protocols interact with each other.


##### RTP protocol stack

In addition to VCR type functionality, RTSP also allows an IPTVCD to request and retrieve a particular item of IPTV content. The fulfillment of this request involves the inclusion of the appropriate VoD servers IP address inside the request command issued by the IPTVCD.

Interactive IP-VoD Client Application

A deployment of a generic IP-VoD system architecture is based on a client/server computing model. This means that a dedicated point-to-point connection is setup between the IPTVCD and the server at the data center. To interoperate with the data center server over this connection the IPTVCD requires a VoD client software application that is capable of receiving IP based VoD streams. The client application presents the IPTV end user with a menu of video assets and associated descriptions on their television screen. The contents of the menu are based on the programming package that the consumer has subscribed to. The technical gathering of this information is called service discovery and varies between networks. For instance, on a DVB network the system used to discover information about available on-demand services is a standard XML record, which is predefined.

In addition to allowing subscribers to select and download specific movies a typical IP-VoD client application also supports content searching and stream control functionality. An implementation of the client IP-VoD application is typically implemented through an embedded HTML browser.

<div id="Browsing"></div>
</br>
<div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/Browsing.png" width="600"></div>

### 3. IPTV Browsing

Many IPTV network operators provide viewers with access to the Web. This can be in the form of either TV-based Web browsing (WebTV) or Walled gardens. TV based Web browsing is similar to browsing on a PC but it is TV based. Since many Web pages are not tailored for viewing on TV, some network operators provide an embedded browser on their IP set-top boxes that change a Web page automatically. Such software can be provided as part of a middleware platform. 

The concept of using a television set to bring Web connectivity has been commercially available for over a decade but due to a whole raft of reasons consumers have continued to reject the use of this interactive TV application. With advancements in IPTV and Web technologies the popularity of accessing Web content via TV applications is expected to grow in the coming years.
Web browsing is a key component of an IPTV system. In the figure below, the structure of a generic infrastructure used by IPTV operators to deliver high speed Web access to their subscribers is illustrated.
As shown, an end-to-end system includes: the IPTVCD Web browser, a HTTP Web server, caching servers, and a high-speed backhaul connection to the Internet.

##### IPTVCD Browsers

Browsers built for IPTVCDs need the same robust functionality found in desktops, but with access to a fraction of the hardware resources. Therefore, they are optimized to run within resource constrained platforms such as set-top boxes, mobile phones, and Internet-enabled appliances. The browser software runs on top of the underlying real-time OS and middleware platforms and typically provides the following functionality:
Displaying Web pages—Putting a Web page on a television screen is very different to displaying the same page on a computer monitor. It must be remembered that the television has been in existence for over a hundred years. Therefore, IPTVCDs employ sophisticated software browsers to ensure that Web pages are easily viewed on a TV screen.
 
##### Technical building blocks of an IPTV browsing system

IPTVCD browsers are able to squeeze the content of a Web page on to a television screen, while limiting the affects of viewing content on a low resolution device. This process is called transcoding and involves repurposing Web content into a simpler format that is suitable for display on a standard television. 
Transcoding can be divided into two broad categories: HTML and Image Transcoding. The transcoding of HTML content includes checking the code for any errors. An example of an HTML error would be the absence of a </html> tag on a standard Web page. Transcoding filters these errors and produces a version of HTML that can be easily rendered by the IPTVCD browser. In addition to checking for errors, the HTML transcoding element is also capable of changing the layout to a TV centric format. For example, the default font size for a Web browser is normally 10 points. If this font size were to be displayed on a television screen, then it would be very difficult to read. Consequently, the transcoding engine will automatically increase the size of the font to 20 or 22 points. This approach means that less text can be displayed on a TV screen than in a comparable area of a computer monitor. However, the text is legible for subscribers that are viewing the page from a distance of 4--5 ft away from the television display. In addition to automatically adjusting font sizes, transcoding takes care of adjusting the size of a page to fit within the width and height of a TV screen. 

Image transcoding is responsible for converting the many image formats used on the Internet to a format that is suitable for an IPTV environment. Flat-color GIFs are processed more readily by IPTVCDs than JPEGs or PNGs. So, for instance, when an IPTV subscriber makes a request for a document on the public Internet, which contains JPEG images, the image transcoder is able to convert the images into a GIF format. In addition to translating the file format, some advanced browsers are also capable of formatting and scaling graphics for a television screen.
As shown in the figure below, an IPTVCD browser consists of a presentation engine that processes and renders a number of different types of open Internet and TV content formats.


###### IPTVCDs supported browser formats

###### A Web Server 

A Web server, also known as an HTTP server, is basically a file server. A Web server’s main function within an IPTV network is to listen for and respond to HTTP requests from IPTVCD browser clients. When a request is received, the server opens a connection to the browser and sends the requested file or Web page. After servicing the request, the server returns to its listening state, waiting for the next HTTP request. HTTP is extremely rapid. According to Tim Berners-Lee, the developer of HTTP, the request is made and the response is given in a cycle of 100 ms. The delays experienced are usually the result of congestion on the IP based network. In addition to responding to requests from browsers, Web servers are also responsible for completing other tasks including
Logging activity on the IPTV network
Protecting Web pages from unauthorized users
Sending requests to peer Web servers on the public Internet
The hardware requirements for a Web server will vary according to the level of interaction between the IP set-top box and the Web server.

##### Caching Servers 

When using a resource constrained device such as a set-top box to browse the Web, it makes sense to incorporate optimized caching within the overall system architecture. The caching servers are normally located at the IPTV service provider’s regional office at the edge of the core IP backbone network. The caching technique employed by IPTV systems involves the storage of popular Web pages on the server. The various caching servers used by an IPTV browsing application use standardized communication protocols to “talk to each other,” thus ensuring that local Web pages are kept current. Caching servers fall into two broad categories: software that runs on a standard server or a dedicated hardware platform.
Note that in addition to the above technologies, a high speed and resilient connection to the public Internet is also required for IPTV browsing services.


<div id="E-mail"></div>


### 4. IPTV E-Mail

From the earliest days of society people have used various systems and technologies to communicate with each other. With the recent explosion of the Internet, the most popular means of communicating between computers is electronic mail (e-mail). With the advent of IPTV, e-mail is now poised to enter the living room.



The figure below shows how an end to end IPTV e-mail solution might look like. As illustrated the major components of a fully built end-to-end IPTV e-mail system include the client software resident in the IPTVCD, a suite of communication protocols, servers, and a firewall located at the IPTV data center.


##### End-to-end IPTV e-mail solution

##### IPTVCD E-Mail Clients 

The IPTVCD with its interactive capability is seen by many as a natural environment for e-mail in the home. The client e-mail application is normally integrated with the IPTVCD middleware and uses the TCP/IP protocol to communicate with the IPTV data center. Modern IPTV e-mail applications fulfill a wide range of functions and let subscribers do more than just send or receive mails. For instance, the attachment of files to e-mails is supported. This might sound like a trivial feature but in the world of IPTV and thin IPTVCD clients the implementation of attaching files poses some technical challenges. For instance, IP set-top boxes do not have the processing power or storage capacity necessary to run popular programs that are needed to open file attachments. Therefore, the IPTV e-mail client needs to convert the attachment into HTML format and then use the browser to display the file. Other features supported by IPTV e-mail clients include personal address books and support for encryption.

##### Networking and Communication Protocols 

E-mail messages are always transmitted in American Standard Code for Information Interchange (ASCII) format. ASCII files are text-only files. The transfer of e-mail messages in an IPTV environment are normally based on Internet mail standards such as SMTP, MIME, IMAP4, and POP3.
SMTP—stands for Simple Message Transfer Protocol. It is used to transfer IPTV mails from the mail server located at the data center to another e-mail server on the Internet, and is designed for reliable and efficient mail transfer. SMTP forms part of the TCP/IP protocol stack, and is used to specify how e-mails should be passed from transmitting to receiving hosts.
MIME—stands for Multipurpose Internet Mail Extensions. MIME is an Internet standard that lets IPTV e-mail clients automatically encode and decode binary files from their original format into a format that is viewable on a television screen. It specifies how non-ASCII messages should be formatted so that they can be sent over the public Internet. Examples of non-ASCII messages include graphic, audio, and video files. This protocol allows IPTV e-mail systems to support much more than just text messages. There are many predefined MIME formats, including JPEG file graphics, and PostScript files.
POP3—stands for Post Office Protocol version 3. It is used by IPTVCD e-mail clients to access messages stored on the mail server.
IMAP—stands for Internet Message Access Protocol, the latest version of this protocol, IMAP4, has similar functionality to POP3 but does support additional features, which are useful for IPTV end users. E-mail searching using keywords while the e-mails remain on the server is one example of an IMAP feature that is not supported by POP3.

##### E-Mail Servers 

Every IPTV subscriber that avails of the e-mail service receives a unique e-mail address and a mailbox. The mailboxes are stored and managed on mail server gateways at the IPTV data center. These servers are connected to the Internet and also interface with the OBSS for billing purposes. The mail server gateway is a software program that runs on a mail server and links the IPTV network through a firewall to the public Internet.


##### IPTV E-Mail

From the earliest days of society people have used various systems and technologies to communicate with each other. With the recent explosion of the Internet, the most popular means of communicating between computers is electronic mail (e-mail). With the advent of IPTV, e-mail is now poised to enter the living room.


The figure below shows how an end to end IPTV e-mail solution might look like. As illustrated the major components of a fully built end-to-end IPTV e-mail system include the client software resident in the IPTVCD, a suite of communication protocols, servers, and a firewall located at the IPTV data center.


##### End-to-end IPTV e-mail solution

##### IPTVCD E-Mail Clients 

The IPTVCD with its interactive capability is seen by many as a natural environment for e-mail in the home. The client e-mail application is normally integrated with the IPTVCD middleware and uses the TCP/IP protocol to communicate with the IPTV data center. Modern IPTV e-mail applications fulfill a wide range of functions and let subscribers do more than just send or receive mails. For instance, the attachment of files to e-mails is supported. This might sound like a trivial feature but in the world of IPTV and thin IPTVCD clients the implementation of attaching files poses some technical challenges. For instance, IP set-top boxes do not have the processing power or storage capacity necessary to run popular programs that are needed to open file attachments. Therefore, the IPTV e-mail client needs to convert the attachment into HTML format and then use the browser to display the file. Other features supported by IPTV e-mail clients include personal address books and support for encryption.

##### Networking and Communication Protocols 

E-mail messages are always transmitted in American Standard Code for Information Interchange (ASCII) format. ASCII files are text-only files. The transfer of e-mail messages in an IPTV environment are normally based on Internet mail standards such as SMTP, MIME, IMAP4, and POP3.
SMTP—stands for Simple Message Transfer Protocol. It is used to transfer IPTV mails from the mail server located at the data center to another e-mail server on the Internet, and is designed for reliable and efficient mail transfer. SMTP forms part of the TCP/IP protocol stack, and is used to specify how e-mails should be passed from transmitting to receiving hosts.
MIME—stands for Multipurpose Internet Mail Extensions. MIME is an Internet standard that lets IPTV e-mail clients automatically encode and decode binary files from their original format into a format that is viewable on a television screen. It specifies how non-ASCII messages should be formatted so that they can be sent over the public Internet. Examples of non-ASCII messages include graphic, audio, and video files. This protocol allows IPTV e-mail systems to support much more than just text messages. There are many predefined MIME formats, including JPEG file graphics, and PostScript files.
POP3—stands for Post Office Protocol version 3. It is used by IPTVCD e-mail clients to access messages stored on the mail server.
IMAP—stands for Internet Message Access Protocol, the latest version of this protocol, IMAP4, has similar functionality to POP3 but does support additional features, which are useful for IPTV end users. E-mail searching using keywords while the e-mails remain on the server is one example of an IMAP feature that is not supported by POP3.

##### E-Mail Servers 

Every IPTV subscriber that avails of the e-mail service receives a unique e-mail address and a mailbox. The mailboxes are stored and managed on mail server gateways at the IPTV data center. These servers are connected to the Internet and also interface with the OBSS for billing purposes. The mail server gateway is a software program that runs on a mail server and links the IPTV network through a firewall to the public Internet.


<div id="CallerID"></div>


### 5. Caller ID for TVs

This IPTV application allows consumers who have subscribed to a caller ID service through their telephone company to view caller information on the TV screen. In other words, when the phone rings a pop-up window appears on the television to notify the end user of the name and phone number of the incoming caller. 

Advanced versions of this IP application allow the simultaneous pop-up of caller ID windows on multiple PC’s and TV screens around the house. A high level overview of the two main components required to deploy a caller ID service on an IPTV network are shown in the figure below and explained in the following sections.
An application server—This server is normally located in the IPTV data center and supports a wide range of telecommunication protocols. When a call arrives, the signal is routed to this server and a communication session is established with the IP set-top box. Additional functions of this application server range, from communicating with the back office provisioning and management systems to managing data transfer across the network.

##### Components of an end-to-end caller ID IPTV application

A client IPTVCD software application—the display of caller ID details on a TV requires the installation or activation of a specialized piece of software on the IPTVCD. This software module integrates with the IPTVCD operating system and is typically branded by the IPTV service provider. This application is responsible for ensuring that the name and number of the incoming caller appears on the subscriber’s TV screen.
The caller ID application can also be used to display notifications of other types of incoming messaging services including voicemails, and text messages. The caller ID for TVs is an extremely popular application amongst IPTV subscribers and is one practical example of how converged services will have an impact on people’s lives in the years ahead.

<div id="Advertising"></div>


### 6. IPTV Advertising

The use of interactive TV as a medium to deliver advertising is rapidly emerging into a mainstream application. The fact that it allows advertisers and service providers to engage consumers with a compelling suite of advertisements is considered to be one of the main drivers of this type of IPTV application. IPTV is capable of supporting a range of different IPTV ad formats, including telescoped long form adverts and integrated links that are embedded directly into the content. 

In addition to the various ad formats, IPTV allows operators to place adverts into both the standard broadcast programming streams and the increasingly popular method of delivering content on-demand. Not only does IPTV advertising provide advertisers with a one-to-one connection with consumers but it also represents a significant revenue opportunity for telecommunication operators deploying IPTV services. The advent of new targeted advertising technologies that run across IP networks are now starting to appear in different IPTV deployments across the world. The two key benefits of these new IP based systems compared to traditional advertising systems that operate over RF based networks are
Two-way capabilities—Owing to the fact that all of the IPTV deployments are operating over bidirectional broadband networks means that these new advertising systems are able to collect and monitor in real-time viewer reactions to advertisements. This feature allows advertisers to immediately gauge the effectiveness of a particular marketing campaign.
Individual IPTVCDs can be addressed directly—The deployment of targeted ad insertion techniques on an IPTV system enables service providers, content programmers, and advertisers to target their advertising messages to individual IPTV viewers. This is a major benefit over current advertising systems, which are limited to targeting commercial advertisements to specific geographical areas.


The functionality provided by this application allows subscribers to retain control of their video content viewing experience while ensuring that they only receive adverts on products and services that align with their interests in an opt-in basis. From an advertiser’s perspective, the availability of accurate user data helps to increase the success of their advertising campaigns by allowing them to focus on viewer’s interests. Service providers also benefit from this level of functionality because it helps to create a new television advertising revenue stream. The six major hardware and software components of a fully built end-to-end addressable advertising system are depicted in the figure below and described in the following sections.

##### IPTV targeted advertising system

Content reception—In an IPTV advertising system, the television channel is typically received from off-air or from a satellite feed and forwarded to the splicer. Special advert markers are sometimes included in this stream, which pinpoint the sections of the video stream that are allocated for ad inserts.
Advert server—Advertisements are typically pre-recorded and stored digitally on this special purpose video server located at the IPTV provider’s data center. The server streams these advertisements to the splicer.
Advert splicer—The purpose of this piece of hardware is to insert adverts retrieved from the advert server into the IPTV streams.
Advertisement management system—This is a piece of software that runs on a PC or server. It ensures that the correct adverts are inserted into the correct IPTV streams at the specified time slots. Some of the more advanced systems support the creation of specific marketing campaigns based parameters such as programming type, geography, and demographic data.
Broadband access router—This router streams the IP video streams with the embedded digital adverts on to the core and access IP networks.
IP set-top box—The targeting of adverts over an IPTV network generally starts with the subscriber who uses their IPTV interface to create a personal profile that outlines the types of adverts they would like to view. This profile information and related viewing statistics is then used by advertising companies to reach IPTV subscribers who have an interest in a specific category of products or services.
The deployment of an IPTV targeted advertising system is rarely implemented in isolation and is usually integrated into an IPTV data center in conjunction with a number of other third-party systems.


<div id="GoD"></div></br><div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/GoD.png" width="400"></div>


### 7. Gaming on Demand (GoD)

IPTV technologies also allow telecom operators to deliver interactive TV gaming applications to their customers. The addition of online gaming applications to a portfolio of IPTV services can not only help to generate additional revenue streams for telecom operators but also reduce customer churn. In addition to subscriptions, IPTV providers can also place adverts in IP based games that connect advertisers with end users. The GoD application allows IPTV subscribers to

play high quality premium games from the comfort of their homes;
play with other gamers connected to the Internet;
participate in text, phone, or emoticon messaging during game play.

The two major components of an IP based on-demand gaming system are depicted in the figure below.
Gaming servers—A client-server computing architecture is generally used to deploy this type of IPTV application. The servers are located at the IPTV data center and typically integrate seamlessly into existing VoD infrastructures. A server may be involved in two types of tasks with the deployment of online games: store the various game titles and interpreting instructions from the IP set-top box.
Online gaming client applications—IPTV gaming applications run locally or remotely, dependent on the hardware capabilities of the IPTVCD. A remote control or specialized joystick is typically used to play the games. The UDP/IP protocol layers of the IPTVCM are used to carry the gaming content both upstream and downstream to the client IPTVCD.
Although games deployed by IPTV systems are a far cry from the advanced games that are played on dedicated game consoles, the level of sophistication used by IPTV games has improved dramatically in recent times and this trend is expected to continue into the future.

<div id="EAS"></div>


### 8. IPTV Based EAS

Digital TV systems based in the United States will typically interoperate with a national system called the Emergency Alert Systems (EAS). 

This system was established in the late 1990s by the FCC and alerts people of danger. Till now, TV and radio were the two primary carriers of these messages but now IPTV systems have started to also provide this level of functionality to subscribers. 

As shown in the figure below, implementation involves the installation of a standalone FCC Type-Certified EAS receiver and character generator at the IPTV data center.

IPTV based EAS network components

Once this device is live on the network, it is possible to automatically send text and digitized audio based EAS alert messages to IPTV end users.

<div id="DVR"></div>


### 9. Digital Video Recording (DVR)

A hard disk needs to be incorporated into the IP set-top box to support DVR functionality; the ability to select programs, digitally record and store live TV content on a local hard disk.



##### IP Set-Top DVRs
The IP set-top DVR category may be subdivided primarily into standalone and multiroom devices.

Stand-Alone IP Set-Top DVRs 
IP DVR set-top boxes serve as a media hub when connected to an in-home networking system and allow IPTV subscribers to
Pause and rewind live programming
Record shows and movies on the set-top hard drive
Replay video content at any time
Most of the components at the core of an IP DVR set-top are almost identical to the parts used to build a standard IP multicast and unicast set-top box. The inclusion of a mechanical hard disk is the main differentiator of this type of IP set-top box. The main functions of the hard disk include
Storing the IP set-top box’s key components of the OS and software code.
Storing system and user data (such as profiles, configuration details, the system registry, updateable system files).
Storing IP-VoD content.
The following section provides a brief overview of mechanical hard disks when incorporated into an IP set-top box.

##### IP Set-Top Hard Disks 
The basic technical architecture of a hard disk that is integrated with an IP DVR set-top comprises of magnetic coated circles of material that contain stored information. 

These circles are called platters and are stacked on top of each other to increase the storage capacity of the drive. Information is read from or stored to the hard disk using read and write heads.
The hard disk is a nonvolatile, bulk storage medium that acts as a repository for video content. The main benefit of this medium versus standard RAM systems is the sheer capacity of these devices and their ability to continue storing contents when the IP set-top box is switched off.
There are generally two types of internal bus interfaces used by drives integrated with IP set-top boxes—IDE and SATA.
Integrated drive electronics (IDE)—The IDE bus also known as ATA (Advanced Technology Attachment) connects the hard drive to the IP set-top motherboard. The IDE standard has been around for many years and has undergone several revisions over time. When integrated into a set-top box an IDE drive is capable of communicating in speeds in excess of a 100 Mbps.
Serial ATA (SATA)—ATA or IDE transfers data in parallel. SATA in contrast to the IDE standard uses a serial bus to communicate data. First generation SATA drives were released in 2001 and are capable of throughputs of 150 Mbps. 

Over the last couple of years, a number of IP DVR set-top manufactures have started to install drives that are based on an extension to the original SATA standard—SATA II. The newer SATA II drives offer higher rate interface speeds compared to their predecessors. The improved read/write times associated with SATA II help to improve the operational efficiencies of next generation IPTV applications.
While most DVR enabled IP set-top boxes use standard hard disks, some storage manufacturers have started to optimize their products for storing and streaming digital video streams. A drive optimized for DVR functionality inside an IP set-top box will generally include such features as
Advanced cooling capabilities—Manufacturers can custom tune the cooling capabilities of IP set-top hard disks to improve overall power consumption of the unit.
Small form factors—Hard disks with a form factor of only 3.5 in. are typically incorporated into IP set-top DVRs. The sizes of these drives will continue to decrease and 1.8 in. hard disk sizes are expected to become a standard feature in IP DVRs over the next couple of years.
Concurrent reading and writing of hard disk—The simultaneous reading and writing of IPTV streams to disks allows consumers to time shift their viewing.
High capacities—Video recording and IPTV streaming are very demanding of storage capacity. Therefore, IP set-top box hard disks come in a range of sizes from 100 GB to 1 TB (TeraByte) capacity. Next generation technologies such as perpendicular magnetic recording (PMR), heat-assisted magnetic recording (HAMR), and holographic recording are expected to exponentially increase capacity of IP set-top box hard disks.
High RPMs (revolutions per minute)—The RPM characteristic of a hard disk measures the rotational speed of the hard disk. Drives that are capable of operating at high RPMs (typically 7200 and above) allow for smooth recording of IPTV content and subsequent playback.

##### Multiroom IP Set-Top DVRs 

With these types of set-tops, IPTV subscribers can receive and watch streamed video content stored on their DVR set-top box in various rooms around the house. Each one of these rooms typically requires an entry level IP set-top box to gain access to the video content. There are two approaches to implementing a multiroom system:

A centralized storage architecture where only one IP set-top box that is connected to a home network includes a hard disk. Under this architecture the DVR functions are executed by the main or master IP DVR set-top box and the remaining non DVR capable digital set-top boxes assume the roles of access devices. The use of the centralized video storage architecture is a significant enhancement, however, IPTV subscribers cannot simultaneously access multiple programs from the DVR. In other words, the master IP DVR set-top box can only play one program at any particular instance in time.
A distributed storage architecture where all IP set-top boxes connected to a home network include a hard disk.

<div id="WGP"></div>


</br><div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/WGP.png" width="650"></div>

### 10. Walled Garden Portal

A walled garden portal is best defined as a Web portal or quasi-Web environment specifically developed for a TV environment. Within a walled garden, a viewer has access to a variety of content such as horoscopes, news, recipes, sports, weather, and internet applications such as e-mail and chat. In addition to providing content, some of the more advanced portals provide the following functionalities:
Registration services for various types of IPTV content services.
Allowing end users to purchase IPTV content services.
Allowing service providers to run promotional campaigns.
Providing content navigation services, which are similar to those provided by the IPTV EPG.
Since content is owned and controlled by the platform provider, only IPTV subscribers have access to a walled garden via their TV. Internet users do not have access. In some cases, IPTV subscribers have access to the public Internet from the walled garden. Each page within a walled garden is designed for TV.

Designing Pages for an IPTV Based Walled Garden Portal 

IPTV service providers and content creators must first consider the differences between a TV and a PC, the circumstances in which they are used and the audience using the IPTV portal. A graphical example of a viewer watching TV is presented in the figure below and described in the following sections.


##### A typical setting in which a person views a TV

A graphical example of the setting in which a PC user typically uses a PC is presented in the figure below and described in the following sections.

##### A typical setting in which a person uses a PC

A number of considerations need to be taken into account when repurposing Web content for an IPTV walled garden portal. The following list provides a set of guidelines for professionals who are involved in developing a portal site for a new IPTV service.
Keep Video Picture in Background When designing a Web page for a TV audience, it is preferable to have the TV picture as the background to maintain consistency and to enliven the Web page. IPTV content creators should provide a choice of semitransparent or opaque backgrounds to the Web page. It is also possible to use audio (like music and voice introductions), video, and animations to energize the material.
Keep Content Concise Considering the medium and viewers’ goals, content in a Web page should not be too long and complex. Content should be provided in easily absorbed chunks and having a large quantity of menus or hyperlinks should be avoided. Since a TV viewer will have less patience than a PC user, ensure fast download and response times.
Choice of Navigation Given that it is difficult to use a PC keyboard while sitting on a soft chair, the navigational device most used for Interactive IPTV applications is a remote control. A remote control should be light and easy to hold in one hand. The buttons should be easy to see and to press, a maximum of 30 buttons is optimal.
Most remote controls have directional buttons and a select button. There should be a clear relationship between the screens and the remote; this is often achieved by linking color-coded onscreen buttons with equivalent remote control function keys.
IPTV providers often supply a wireless keyboard with a remote control so that a viewer can make the most of features such as e-mail, chat, t-commerce, and informational elements. A wireless keyboard contains most of the buttons that are found on a PC keyboard. They also include iTV specific buttons that vary according to brand. Seeing as, not all IPTV viewers have a wireless keyboard or if they do, it is cumbersome to use in a TV setting, it is best to assist navigation by 
Keeping navigation simple
Avoiding scroll bars or allowing limited vertical scrolling 
Presenting choices in lists 
Minimizing demands on the viewer to type
Arranging elements in grids for remote-control navigation (like EPG grids)
Linking functions to remote-control keys
Avoid multilayered navigational trees
Remove nonessential links and options
Use pull-down menus instead of navigation links
Have site navigation at the top with sub navigation at the bottom
Add back and next links to each page
Because Web pages are built for a mouse-controlled onscreen cursor, it is not possible to design for navigation in a TV Web page in the same way.

Characteristic Description
TV audience The TV audience
is culturally, intellectually, and technically diverse;
age profile encompasses all ages—from the very young to the very old;
uses the TV principally for entertainment purposes;
does not expect demanding interaction;
has, on average, a low level of computer skills.
Distance from TV A TV viewer views the TV at a distance of approximately three to four and a half meters (10--15 ft). Everything displayed on screen should be large enough for viewers to see from a 5 m distance. Font size should be at least 18 point and screen elements should be arranged well spatially, to create a cleaner and clearer screen.
TV content A TV viewer is most used to the seamless display of content in motion with audio, that is, standard television. Viewers have become more and more familiar with text in the form of program guides in large font. In Europe, many viewers have become accustomed to using teletext that is overlaid on the TV picture. It is available with opaque, semitransparent, and transparent settings.
Navigational devices A TV viewer uses a remote control and/or a wireless keyboard as navigational devices. The remote control is most prevalent because it is a handheld device and relatively inexpensive. The keyboard can be cumbersome to use while sitting on a soft chair but is useful for text input. The context of viewers’ television experience involves going up and down through broadcast channels.

Using a PC Characteristic Description
PC users PC users
use the PC mainly for information and communication (often work-oriented);
expect lots of text, complexities, and problems;
often expect to wait for something to download;
have moderate to high computer-skill levels.
Distance from PC 
The PC user is usually about half a meter (2 ft) from his or her PC.
Along with high resolution and a picture that adheres to the edges of the computer monitor, the screen allows for a lot of detail. The standard text size is 11 point. PC content PC users are used to static, clear, and often colorful display of content in Web pages. There are few restrictions to color or color combinations. PC Web pages generally consist of menus, sub, and drop-down menus; lots of text in 11 point font, vertical and horizontal scroll bars, numerous hyperlinks, search features, crisp graphics, and audio and video requiring plug-ins Navigational devices Usually have a keyboard and mouse as navigational tools or similar equivalents.
PC setting Many PC users are accustomed to viewing Web pages in a focused setting such as in a home or work office while sitting on a “hard” chair, at a desk (often both are ergonomically designed).

##### TV setting

Generally, viewers watch TV in the “living” room or area of their home. Typically, this is a comfortable area with soft seating and lighting to create an environment conductive to relaxation.
Understand the limited Memory and Speed of IPTVCDs Particularly IP Set-top boxes Set-top boxes range in CPU power, operating systems, and memory capacities. However, a set-top box on average will have 8 MBs of RAM and a processing speed of 400 MHz while most PCs will have at least 1 GB of RAM, a 100 GB hard-drive, and a processing speed of 4 GHz. Viewers will not be any less impatient with loading times if aware of these differences. Loading and response times should be short.
Understand the Characteristics of Analog TV The resolution and the safe area affects how a Web page looks on a TV screen.
Resolution—Owing to higher resolutions, the picture display on a computer monitor is much crisper and more stable (e.g., color) than an analog TV display. Resolution is generally measured in terms of pixels. The more pixels there are in a display, the better the resolution. The manner in, and speed at, which a picture display is transmitted to the screen are also determining factors.
TV safe area—Content on a full screen might be obscured because of overscanning or the casing of a TV-set. That is why it is important to determine the safe area of a screen. The safe area of a screen is the area where the audience is guaranteed to see content (with few exceptions) despite the brand or style of TV set. TV signals usually overscan the edges of the display so that the TV picture appears without “fringes.” In addition, the amount of the display area covered by a TV’s casing depends on the TV set.

Minimize Download Times 
To minimize download times
(1) reduce amount of data to be downloaded—If there are fewer elements on the screen that need to be downloaded, the overall download time will be reduced.
(2) design pages to fit within the safe area of the TV screen—If pages fit the safe area of the TV screen, the IP set-top browser does not need to spend time resizing large images and tables.
(3) anticipate the IPTV viewer’s next page—While the viewer is looking at the current page the next one can be downloading.
(4) insert a fast-downloading introductory scene in animations—While the introductory scene is playing, the remainder of the animation can be downloading.
(5) use television or a color as a background—It is best to avoid putting background images other than television or a plain color as a background on the Web page.

Identify the Types of Signals Used by Target Televisions 
There are two primary types of video signals used by analog televisions: composite and S-video input. In composite video, red, green, blue (RGB), and sync information are combined into one signal going into the TV; in order to transmit this picture, the TV must separate the signal into its four components, which results in some distortions and a degraded picture quality. S-Video provides an improved mechanism for carrying signals resulting in cleaner and sharper pictures. Content developers need to be aware of these differences when customizing applications for an IPTV platform.
Avoid Color Problems TV sets with a composite signal usually generate visual artifacts. Artifacts are distortions of display, content, or sound caused by a limitation or malfunction in the technology used. Artifacts can be minor or extreme.
Such artifacts do not appear on computer monitors. If the chrominance difference between two colors is great, an artifact known as “chroma crawl” is created on a composite video signal. Wherever two contrasting colors meet, dots appear to crawl. Sometimes they can form a shape and move across or down the screen. This can make text and images appear unclear or distorted. It is possible to avoid chroma crawl by using colors of the same hue but with varying luminance.
Minimizing Color Problems By eliminating chroma crawl IPTV content creators restrict their choice in colors. However in many cases, it is sufficient to just minimize the effect. Minimizing chroma crawl means reducing the chrominance distance between adjacent colors. This is possible by replacing vivid colors with pastel relatives, for example. In addition to chroma crawl there are other TV-generated color problems to consider:
Hot colors—To reduce the over-vibrant appearance of colors, reduce saturation by 80 to 85%.
Bleeding—Bleeding can occur with either a composite or a S-video signal.
Adjoining colors appear to bleed into each other. Bleeding can be remedied in the same way as chroma crawl.
Moiré effect—Moiré patterns occur with interlaced scanning when contrasting colors (like, black and white in a herringbone pattern) appear 
in close proximity. Moiré effects vary depending on colors. The area around the pattern can produce a shimmering effect or it could produce a red glow, for example. It is possible to avoid Moiré effects by avoiding detailed patterns.
Blooming—In interlaced scanning, brighter scan lines are wider than darker ones. Therefore, if there is a large number of alternating bright and dark scan lines grouped together the vertical sides appear to wave in and out. Blooming is highlighted when you have vertical lines, like those in a table.
Flickering—Flickering is caused because TV displays are interlaced. Without a flicker filter, a thin horizontal line just one-pixel thick would appear to flicker on and off. Horizontal lines should be at least 2 pixels in width. Similarly, horizontal edges between two contrasting colors would pulsate.
There is a gradual move across the world from old analog TV sets toward digital and high definition televisions, which deliver better picture, sound, and overall stability. Eventually there will be global deployment of these. When this happens the development of Web pages for IPTV Web portals will become more straightforward. Until that happens, content creators will need to comply with the various guidelines outlined above. From a market demand perspective, TV viewers are more accustomed to watching TV than viewing a Web page on its screens. However, this author is more optimistic than ever that the concept of walled gardens will eventually catch on and firmly believes that IPTV will act as a catalyst for increasing the popularity of this application.

<div id="IM"></div>


### 11. Instant IPTV Messaging

This application uses “presence technology” to allow subscribers to use their televisions to participate in interactive chat forums. The network service provider decides on the types of chat forums that are available to their customer base. From a technical perspective the IPTV operator needs to install a powerful community chat server in the headend. Chat servers are easily customizable and seamlessly integrate with advertisement banners.
The client IPTV application has very low memory and processor requirements and makes it very suitable for use in IPTVCDs. Most IPTV chat programs offer one-to-one and one-to-many communication channels. 

New versions of IPTV messaging software applications allow interactive TV designers to split the TV screen into two frames. The first frame includes the forum, while the second frame displays the related TV program.

<div id="Commerce"></div></br>
<div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/Commerce.png" width="700"></div>

### 12. IPTV-Commerce

IPTV-commerce supports business activities and enables viewers to purchase goods through a TV using a remote control instead of a keyboard and an IPTVCD. The term IPTV-commerce can refer to online shopping, instant shopping, online betting, and home banking. In the case of instant shopping, end-users can purchase a product featured on an advertisement without having to leave the channel they are watching. 

The ability to facilitate the provision of e-commerce via an IPTV platform helps to enhance the overall revenue stream of service providers. Security measures that apply to PC based e-commerce also apply to IPTV-commerce. This is an ideal application for people who are not comfortable with using their PC to buy online.

<div id="Social"></div></br>
<div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/Social.png" width="450"></div>

### 13. IPTV Social Networking

The popularity of Internet based social networking sites has grown rapidly over the past couple of years. IPTV facilitates the expansion of the phenomena of social networking onto the television. Implementing a social networking environment on a TV set requires specialized software on both the IPTVCD and the backend servers. 

Typical features supported by this type of interactive IPTV application range from buddy lists that allow IPTV subscribers to view what their friends are watching on television to real-time chatting while watching the same program.

<div id="Localized"></div>


### 14. Localized Video Content

The deployment of localized video content is seen by many telecom operators as a differentiator for IPTV. Most of the content delivered by the media nowadays has a countrywide or international focus, with a limited emphasis on providing content that is local to particular geographical communities. With IPTV, telecom operators now have the ability to offer local information to their subscribers. The local content IPTV application typically allows subscribers to retrieve local weather, schedules for garbage collection, school announcements, results of sporting events, and traffic videos on their televisions.

<div id="Parental"></div></br>


<div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/ParentalControl.jpeg" width="500"></div>


### 15. Parental Control

Parental control are processes that allow a person (such as a parent) to control the access rights of another person (such as a child).
IPTV networking platforms also include filtering systems that allow telecom operators and subscribers to restrict access to certain on-demand titles or broadcasting channels that contain inappropriate content. Channels or VoD titles requested by an IPTV subscriber are checked against a database of objectionable content. If the server finds that the material is rated, it will not allow that video asset to be passed on to the person making the request. The application itself uses PIN codes to enforce content filtering regulations.

<div id="Personalized"></div>


### 16. Personalized Channels

The ability of IP based technologies to allow subscribers to create their own TV programs and to broadcast this on personalized channels is yet another application that helps to differentiate IPTV from traditional RF based TV services. Taking into account continuous evolution of services and end user’s requirements, personalized IPTV services are another hot research area. Users can perform trick mode operations like pause, rewind when watching live channel. When someone missed some TV shows, he or she can use rewind TV channel to desired time and watch at their feasible time. Thus, personalized IPTV services enable users to access and consume what they want, when and where they want in a personalized way. 

<!--</br><div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/Personalized.png" width="500"></div></br>-->

In personalized IPTV services environment, we also need to know about content delivery operation and channel allocation algorithm according to service types such as linearTV(i.e., live TV), time-shifted TV and video on demand (VoD).

<div id="Weather"></div></br>
<div align="center"><img src="https://github.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/blob/master/Images/Weather.png" width="700"></div>

### 17. Weather Forecast

Many IPTV network operators provide viewers with access to the weather forecasts information. IPTV based weather application is similar to weather applications that are designed to work on a PC but it is TV based. With this service you can have dynamic weather information right on your TV screen. This fun-to-use application provides current conditions and forecasts, as well as localized and accurate weather information for wherever in the world. More advanced versions might also provide the subscriber with, severe weather alerts for upcoming extreme weather conditions, updated each hour, including hourly forecasts and information for the next hours and days, animated radar and satellite images, videos, and even interactive weather maps.
IPTV network operators provide an embedded software application on their IP set-top boxes that receives data about current weather conditions and displays this information on the TV screen. Such software can be provided as part of a middleware platform.
Weather application is the most popular interactive service of an IPTV system. In the figure below, the structure of a generic infrastructure used by IPTV operators to deliver high speed access to weather information to their subscribers is illustrated. 
As shown, an end-to-end system includes: the IPTVCD weather application, a HTTP Web server, and a high-speed backhaul connection to the Internet.


##### Technical building blocks of an IPTV weather forecast service.

##### IPTVCD Weather Application

The weather application written for IPTVCDs need the same robust functionality found in desktops, but with access to a fraction of the hardware resources. Therefore, they are optimized to run within resource constrained platforms such as set-top boxes, mobile phones, and Internet-enabled appliances.
The weather forecast software runs on top of the underlying real-time OS and middleware platforms and typically provides the following functionality:
It gives you instant access to real-time local weather and alerts you whenever severe storms threaten. You're just one step away from detailed information on your local weather conditions as well as your favorite cities worldwide. More advanced versions can also provide:


weather maps
animated radar
hourly and daily forecasts
local/national maps
satellite images
weather alarms
hurricane central
weather videos
severe weather alert
weather trivia, photos and cartoons
weather news
customizable look & feel

It might even present the subscribers with weather and health information for the exercise enthusiast or doctors and those with health concerns - arthritis, asthma, flu, migraine allergies and more.
The weather application is pre-embedded in the client’s IPTVCD and works on top of the IPTV middleware.

##### A Web Server
 
A Web server, also known as an HTTP server, is basically a file server. A Web server’s main function within an IPTV network is to listen for and respond to HTTP requests from IPTVCD weather application clients. When a request is received, the server opens a connection to the application and sends the requested weather forecast information. After servicing the request, the server returns to its listening state, waiting for the next HTTP request. HTTP is extremely rapid. According to Tim Berners-Lee, the developer of HTTP, the request is made and the response is given in a cycle of 100 ms. Therefore the viewer will always have access to weather information that is current and up to date. In addition to responding to requests from applications, Web servers are also responsible for completing other tasks including:
Connecting to various weather servers through the Internet;
Checking for new information periodically and keeping the data up to date.


The hardware requirements for a Web server will vary according to the level of interaction between the IP set-top box and the Web server.
We should note that in addition to the web server and the weather application, we also need a broadband connection to the Internet to deploy this service on an IPTV platform.
