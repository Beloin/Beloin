- 👋 Hi, I’m @Beloin
- Computer Engineering Student, enthusiast on the low level aspect of computers. I like to know how really do things works from bit to bit!
- Email:  beloin.rodrigues@gmail.com
- LinkedIn: [Beloin Sena](https://www.linkedin.com/in/beloin-sena-8374a11a9/)


# Projects

My main goal is become a really good Distributed Systems engineer, focusing on Microsservices and Data Pipelines. I will list a few of my projects below.

## AI and Agentic Harness

### [PDF Generator](https://github.com/Beloin/PDFGeneratorBack)

> Rust, Golang, MCP

Back-End for chat-edited PDFs and slideshows. Runs its own LLM harness: a Rust chat loop asks an AI to edit PDFs and slides and gives it tools via MCP calls. Rust fetches tool schemas through MCP `tools/list` at the Go server's `/mcp` endpoint, then turns LLM tool calls into MCP `tools/call` requests.

<div align="center">
  <img src="https://raw.githubusercontent.com/Beloin/PDFGeneratorBack/master/docs/pdf_edit.png" />
</div>

## Golang Projects

### [Distributed Contacts Server](https://github.com/Beloin/DistributedContactsServerPPD)

> Golang, C++ for Frontend using QT

Distributed servers to save Contacts. User can connect to any three know "DNS", using linux hosts to simulate a DNS server. All three servers connect to eachother using Lamport Clock to keep track of changes.

![image](https://github.com/user-attachments/assets/be163ed6-d2c7-4b11-ad51-02c09b74916e)

Example of `Server 1` connected with `Server 2`.
![image](https://github.com/user-attachments/assets/7b57b0e6-ff28-499f-8695-a6be75321464)

Frontend usage:
![image](https://github.com/user-attachments/assets/f0c151f8-e30c-4020-afdf-676810494728)

## C/C++ Based projects

### [Swarm Engine](https://github.com/Beloin/SwarmEngine)

> C, Linux and OpenGL

Swarms are naturally observed in insects and animals, where the individual activity are suppressed by the group will. Here I implemented a small Swarm engine using OpenGL (Graphics Computer API), GLFW and GLAD to copy and simulate the swarm behaviour.

<div align="center">
  <img src="https://github.com/Beloin/SwarmEngine/blob/master/resources/multiple-swarm-multiple.gif"/>
</div>

### [2DPhysicsSimulator](https://github.com/Beloin/2DPhysicsSimulator)

> C

A small Physics engine implemented in C. Used in the Swarm Engine to act as the main engine.

<div align="center">
  <img src="https://github.com/Beloin/2DPhysicsSimulator/blob/master/resources/AABB.png"/>
</div>

### [TWAMP C++ Implementation](https://github.com/Beloin/TWAMPCpp)

> C++, Linux and Network

Implementation of TWAMP protocol using C++ and Linux raw socket calls.

<div align="center">
  <img src="https://github.com/Beloin/TWAMPCpp/blob/master/resources/Twamp_overall_CLIENT_SERVER.png"/>
</div>

### [Solitaire Game](https://github.com/Beloin/PPDOneLeftGame)

> C++, QT, Network and Linux

A solitaire game implementation in C++ and QT using raw socket calls and custom protocol implementations. The implementation consists of a Server and a Client.

<div align="center">
  <img src="https://github.com/Beloin/Beloin/assets/48112126/79f83426-180d-4e67-99a7-cc7714b37747"/>
</div>

<!---
Beloin/Beloin is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
