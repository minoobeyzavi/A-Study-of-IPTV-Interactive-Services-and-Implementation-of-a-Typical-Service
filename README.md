## Review of IPTV Interactive Services and Implementation of a Typical Service
An interactive service is one that enables user to receive a transmission of data specially created for the recipient, or upon request, whether or not as part of a program, which is selected by or on behalf of the recipient.
Interactive services present users with various capabilities. The service provider can combine these capabilities with other services to create two-way communications with the client. The application is implemented to be used on a platform, however it has the least confluence with the main processes of its platform and independently runs and interacts with the user.

### Commercial Innovation Strategies
 1. Adding supplemental features to existing services
 2. New interaction-based services
 3. Side-mode integration of existing services
 4. Personalization & thematic specialization of existing services
 5. Appending content-oriented interactions to existing services

![alt tag](https://raw.githubusercontent.com/minoobeyzavi/Review-of-IPTV-Interactive-Services-and-Implementation-of-a-Typical-Service/master/img.png)


### Interactive IPTV Applications

As the transition from all things analog to digital continues, iTV is becoming more and more prevalent. Thanks to increased bandwidth in new networking infrastructure and the great carrying capacity of the compressed digital signal, interactive content can be offered to more and more householders. iTV describes the phenomenon whereby users are enable to actively engage with content on their TV screens. iTV adds an extra layer of functionality to IPTV beyond on-demand and linear programming services.


It can provide viewers with access to further information, communication applications, and the facility to respond to interactive programming. Deployment of interactive applications involves the transition from one-way to two-way communications and passive to active viewing and viewer control. Applications and programming are transmitted to viewers’ set-top boxes and viewers can interact by using a navigational device such as a remote control or a wireless keyboard. Information sent by viewers is directed from the set-top box to a return path to the host’s network server. Deployment of interactive applications has occurred because a digital signal, which is compressed and transmitted at higher speeds in binary code, can carry more interactive content and numerous channels. iTV is distributed to people’s homes by terrestrial, cable, IPTV, and satellite television providers, each of these groups are consistently battling for a place in the viewers’ homes. All of these providers encourage viewers to subscribe to their pay TV, broadband, and telephone services and usually, they offer a variety of packages, which are designed for different audience types and the different budgets of their audiences.
In addition to allowing subscribers to watch linear video programming, IPTV brings Web-like interactivity to the traditional TV viewing experience. It allows service providers to differentiate their offerings from traditional television services. For consumers it allows them to view hundreds of channels, simultaneously record TV material, and access a range of interactive TV services including

### Types of Commercial Interactive Services
 1. Electronic Programming Guide
 2. VoD
 3. Browsing
 4. E-mail
 5. Caller ID
 6. Advertising
 7. GoD
 8. EAS
 9. DVR
 10. Walled Garden Portal
 11. Instant Messaging
 12. IPTV-Commerce
 13. Social Networking
 14. Localized Video Content
 15. Parental Control
 16. Personalized Channels
 17. Weather Forcast

Interactive television will provide genuinely useful applications that enhance the overall user experience of IPTV. Interactive services must be seen as part of the overall infrastructure of delivering television – not just a bolt on.
To get the right interactive services to meet consumer demands will require experimentation. Content providers, broadcasters and network owners need to develop, trial, refine and roll-out interactive services. A lot has been learnt over the past ten years about interactive TV. This knowledge can help inform the design of interactive services for IPTV.


 
#### Electronic Programming Guide

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




##### End-to-end IPTV EPG system

##### IPTV EPG Application Server 

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


The EPG network architecture described above relies on the ability of the
network and backend servers to respond immediately to EPG instructions. On some occasions IPTV end users may experience delays due to congestion or other issues that slow down the processing of EPG requests. Where this occurs on a regular basis, service providers have an option of using an architecture that involves processing the EPG locally on the IPTVCD. Under this approach the basic EPG application normally resides in the IPTVCD’s storage system and accesses current meta-data from the IP network. Local storage of the EPG application speeds up broadband network response times for the end-user because it launches and operates immediately once the IPTVCD is powered on.


### Weather Forecast

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
