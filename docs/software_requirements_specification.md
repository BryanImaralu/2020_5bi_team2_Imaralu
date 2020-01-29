# Software Requirements Specification

# For

# Team 2

# September 23, 2010























Team 2



| Table of Contents |
| --- |
| 1        Introduction        |
| 1.1        Overview        |
| 1.2        Problems Introduction        |
| 1.3        Scope        |
| 1.4        Project Perspective        |
| 2        General Design Constraints        |
| 2.1        Interface        |
| 2.2        Hardware Interface        |
| 2.3        Use Case Diagram        |
| 2.4        Software Interface        |
| 2.5        Mandated Constraints |
| 2.6        Assumption and dependencies|
| 2.7        Data Flow Diagram|
| 2.8        E-R Diagram |

# 1 Introduction

## 1.1 Overview

There are numerous products available that allow for real time &quot;chatting&quot; over the Internet. The purpose of this project is to implement a Java based chat application that will allow users with an internet connection to engage in private and public conversations. The development of this project centered on the development of a message protocol that would allow the application to properly log in users, send messages, and perform system maintenance.

## 1.2 Problems Introduction

- .This project is to create a chat application with a server and clients to enable the clients to chat with many other clients in the same common chat group.
- .This project is to simulate the multicast chatting. In the case of multicasting when a message is sent to a group of clients, then only a single message is sent to the router.
- .The main purpose of this project is to provide multi chatting functionality through network.
- .This project can play an important role in organizational field where employees can connect together through LAN.

## 1.3 Scope

 Broadcasting Chat Server Application is going to be a text communication software, it will be able to communicate between two computers using point to point communication. The limitation of Live Chat is it does not support audio conversations. To overcome this limitation we are concurrently working on developing better technologies. Companies would like to have a communication software wherein they can communicate instantly within their organization. The fact that the software uses an internal network setup within the organization makes it very secure from outside attacks.







## 1.4 Project Perspective

- The system to be developed here is an Chat facility. It is a centralized system. It is Client-Server system with centralized database server. All local clients are connected to the centralized server via LAN.
- There is a two way communication between different clients and server. This chat application can be used for group discussion. It allows users to find other logged in users.
-  **No need of Internet connection:** Existing system requires Internet connection; whereas in the proposed system only Intranet connection i.e. only a LAN connection is required. This system is useful for those who can not afford to have an Internet connection. For example: schools, colleges, small companies, etc.
-  **Conference possible on LAN:** Usually on LANs connections conferencing is not possible. The proposed system allows the LAN users to create and participate in conference. This makes communications possible among number of LAN users simultaneously.

# 2 General Design Constraints

## 2.1 Interface

- This application interacts with the user through G.U.I. The interface is simple , easy to handle and self-explanatory.
- Once opened, user will easily come into the flow with the application and easily uses all interfaces properly.
- However the basic interface available in our application is
  -  Title panel
  - Content panel
  - Admin panel. Keyboard

## 2.2 Hardware Interface

Minimum requirements will be as follows:

- 4 GB RAM required.
- Processor with speed of 3,5Ghz.
- Internet or LAN connection.
- MOUSE: 2 or 3 button mouse
- KEYBOARD: 101 key

## 2.3 Use Case Diagram


## 2.4 Software Interface
-	Notepad++ is a text editor and source code editor and provides an environment for developing HTML, jsp, JavaScript many other editing purposes. 
-Coding done in java so required JDK 8.0 and above for run java programs. Operating system (such as window 7, 8, xp, Linux etc).

## 2.5 Mandated Constraints
- The application does not by any means open the web browser. If user wishes to open the web browser he must open it externally. 
- The system need to be permanent connected with internet.
## 2.6	Assumption and dependencies
-	There should be LAN or internet connection. 
- Clients should know each other. 
- There can be multiple clients.
## 2.7 Data Flow Diagram


## 2.8 E-R Diagram

