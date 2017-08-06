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
subscriber to use the network. You merely need an AeFi address and a little bit of the AeFi token to get going. 
The exchange of tokens for data is documented by the formation of an ethereum-based smart contract between two 
parties (a host, and a client). The special sauce of this project lies in the gateways/routers, which have a 
secured data meter that is used to verify the amount of data transferred between the client and host. Once the user
disconnects, or consumes all of their token, the host will terminate the transaction by issuing 

2) Mobile client software to run on iOS and Android handsets. This software will need to be able to arbitrate 
connections with the AeFi gateways, and "hop" between these networks to improve the customer experience. 
The mobile app will originate or connect the client AeFi address, allow a client to directly purchase AeFi tokens 
(if they do not already have any), and deliver the "terms of use" to which all must comply (i.e. don't use this 
novel tool for evil). There is a UI/UX component, so both mobile handset designers and developers are needed for 
this challenge, as well.

/******************************************************************************/

-- Future Work --
At this time, it is all future work. But we see that as the AeFi network grows in size, and more gateways appear for
clients to connect to, we'll add an incentive structure for gateway hosts who to compete on delivering the fastest speeds. 
An interactive "data priority scheduler" will also be developed that would allow the client to dictate how fast 
they need to move data and can choose alternative modes of transport (e.g. full wireless mesh networking, 
rather than over an ISP's landline). Another service the AeFi network may offer: security. Embedded VPN in the router
could prevent both the ISP from viewing the transmitted data. Ideally, the client's data is also hidden from the host, although
it is not clear how that would be accomplished, at this time.

The project will be broken up into phases. Just like ethereum, we'll need someone who can come up with catchy names for
each of these. For now, they are:
Phase I. To get going, a "hello world" type demonstration wherein we connect mobile clients to a host, exchange tokens 
for data, and verify that the transfer took place.
Phase II. ???
Phase III. Profit! Actually, the opposite. Aetherfy, LLC will configure and sell out-of-the-box wireless gateways 
that are needed to build the AeFi network. But as an open-source project, the software will be free for others to download,
install, adapt, and run on their own. The act of enabling users to share their excess wireless bandwidth with each other 
will drive down the cost of data for everyone, and is wholly disruptive to existing mobile data business models. 
The AeFi network, as a service, keeps money in the user's pocket, and out of the hands of the service provider. 
While this may hurt corporate profits (as suggested above), it is this liberation of data that will also enable more 
connected devices, greater performance, and heretofore unimagined creations. 

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

