# AeFi
Git repository for the AeFi project (pronounced ether-fye). Brought to you by Aetherfy, LLC.

URL http://aetherfy.com/aefi/

/******************************************************************************/

-- Terms of Use --
This open-source project is subject to the GNU General Public License Version 3, released 29 June 2007.
The full text of the GNU GPL can be found here: https://www.gnu.org/licenses/gpl-3.0.txt

Usage of the AeFi service is subject to the terms of use defined here: http://aetherfy.com/aefi/terms.html

/******************************************************************************/

-- About AeFi (the light version) --
AeFi is the mobile data "last mile" unchained. Using go-ethereum atop wireless routers, we are building a 
trustless WiFi network to supplant existing mobile data networks.

-- About AeFi --
What is AeFi? AeFi is a network of wireless gateways and clients that share and consume unused 
capacity in their home wireless routers as an alternative to cellular data. At the current price, 
even an "unlimited" cellular plan costs $40/mo, so if you use 4GB/mo, that works out to $10/GB for
 data, which is still very expensive. The AeFi project is a push to reduce the cost of mobile data 100X, 
or to <$0.01/GB, merely by empowering individual users to share the wireless. As much as we hate the analogy, 
it is easily described as the "Uber of your wireless router."

With the advent of voice-over-IP telephony services, Whatsapp, and now mobile handsets that automatically push 
call traffic over a wireless network (when available), the technology exists to start cutting the virtual cord
between users, and the phone companies. We can see that real, usable services are emerging that leverage these
technologies, such as GoogleFi and Xfinity Mobile (neither of which are affiliated to the AeFi project, and are 
trademarks of their respective owners). But those services still cost too much, and they are charging users 
to use devices that they already own. So AeFi cuts out these plunderous middlemen. 

The AeFi project is an open-source development project for creating:
1) A wifi gateway (hardware + software) that will share its network connection to AeFi clients. 
Collectively, the gateways form a "last mile" network of wireless nodes that AeFi clients can hop to/from, 
as an alternative to using a cellular network. Unlike ISP-based mobile hotspots, you do not have to be a 
subscriber to use the network. You merely need an AeFi address and a little bit of the AeFi (AEF) token to get going. 
The special sauce of this project lies in the gateway/router, which must have: 
1) A means of securely metering data, and
2) A means of debiting the client's token account automatically.

Once the client disconnects, or consumes all of their token, the host will terminate the transaction by closing the 
connection with the client, accumulating the data/token that was spent, and then using the account details provided 
by the client to debit the client account.

2) Mobile client software to run on iOS and Android handsets. This software will need to be able to arbitrate 
connections with the AeFi gateways, and "hop" between these networks to improve the customer experience. 
The mobile app will originate or connect the client AeFi address, allow a client to directly purchase AeFi tokens 
(if they do not already have any), and deliver the "terms of use" to which all must comply (i.e. don't use this 
novel tool for evil). There is a UI/UX component, so both mobile handset designers and developers are needed for 
this challenge, as well.

/******************************************************************************/

-- Progress --

Week of 8/6/2017: 
1. Installed LEDE/OpenWRT on linksys WRT1200AC router. 
2. Cross-compiled go-ethereum for Linux and ARMv7 CPU architecture. 
3. Loaded go-ethereum binary onto router, but it fails to run, at the moment.
4. Mounted 64GB USB thumb drive on router. The drive will store a light version of the ethereum blockchain.
5. Began looking into LEDE SDK, and trying to debug #3.

-- Future Work --
At this time, it is all future work. But we see that as the AeFi network grows in size, and more gateways appear for
clients to connect to, we'll add an incentive structure for gateway hosts who to compete on delivering the fastest speeds. 
An interactive "data priority scheduler" will also be developed that would allow the client to dictate how fast 
they need to move data and can choose alternative modes of transport (e.g. full wireless mesh networking, 
rather than over an ISP's landline). Another service the AeFi network may offer: security. Embedded VPN in the router
could prevent both the ISP from viewing the transmitted data. Ideally, the client's data is also encrypted and not interceptable
by the host, e.g. truly "trustless" although it is not clear how that will be accomplished, at this time.

The project will be broken up into phases. Just like ethereum, we'll need someone who can come up with catchy names for
each of these. For now, they are:
Phase I. To get going, a "hello world" type demonstration wherein we connect mobile clients to a host, exchange tokens 
for data, and verify that the transfer took place.
Phase II. Beta network buildout. We issue some test tokens to a small network of beta testers. We have a router-flashing
party where people come in, and we'll flash the software on their routers, and help them get set up. The ultimate goal is to have 
a group of users in a concentrated geographical area that can serve as a test bed and a small-scale simulation of a much larger
network. 

Phase III. Liberty! Aetherfy, LLC will configure and sell out-of-the-box AeFi gateways on an as-needed basis to help build 
the AeFi network. But as an open-source project, the software will be free for others to download,
install, adapt, and run on their own. The act of enabling users to share their excess wireless bandwidth with each other 
will drive down the cost of data for everyone, and is wholly disruptive to existing mobile data business models. 
The AeFi network, as a service, keeps money in the user's pocket, and out of the hands of the service provider. 
While this may hurt some stakeholders' profits, it is this liberation of data that will also enable more 
connected devices, greater performance, better privacy, and heretofore unimagined creations. 

/******************************************************************************/

-- Contributors (NEEDED) --
We are currently seeking open-source contributors with experience creating smart contracts and ERC20 tokens on the 
ethereum platform. We need embedded hardware and software engineers with experience using OpenWRT and linux. 
Engineers with LAN, cellular, and wireless networking knowledge are needed most of all. 
UI/UX designers are evidently an important piece, too. If you'd like to talk about working on the project, 
please send us an email at info@aetherfy.com.  We appreciate your support on this important project!

/******************************************************************************/

-- Support the Project --
At this time the AeFi project is fully bankrolled by David White (some guy). If you wish to support building the project, 
and taking it out of the livingroom, then please consider making an ethereum donation here:

cd0e89f5c49d564097fb3f16de93c98861ca3639

Thank You!

Dave White
(C) 2017 Aetherfy, LLC

