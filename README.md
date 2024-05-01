**Note**: As a first-year university student, I am just beginning to learn programming and exploring the world of 
software development. Therefore, the implementation presented here might not reflect best practices or advanced techniques. 
This project was whipped up with a pinch of ChatGPT's magic, so the homework might be more of a whimsical rollercoaster than a stroke of sheer brilliance!^^

Assignment-3:
NODA A    -------   Smart Contract Server ------- Node B

Node A to Smart Contract Server:
1.Node A wants to obtain the private data of node B

Smart Contract Server to Node A:
2. Node A initiates a smart contract

Smart Contract Server to Node B:
3. The Contract server sends the public kex PKa(Sign,Timestamp) of node A to node B

Node B to Smart Contract Server:
4. Node B uses the public key PKa(Sign, Timestamp) of node A to encrypt the private
data and upload it

Smart Contract Server to Node A:
5. Node A obtains encrypted data from the blockchain network and uses the private key
SKa to decrypt it

READme: 
# Secure Communication System Proof-of-Concept (SCS_PoC)

## Important Notice
This project is a Proof-of-Concept implementation showcasing the basic mechanisms of secure communication.

There are 2 Classes: Server.java and Client.java
I have added comments in the Classes where I thought necessary.

This project demonstrates a simple Proof-of-Concept implementation of a secure communication system using Java. :-) 
The system consists of three main components: 
A Smart Contract Server and two clients (Node A and Node B) engaging in encrypted communication mediated 
by the Smart Contract Server.

## Installation and Execution

1. **Clone the Project**: Clone the project to your local machine from the Github repository:

    ```bash
    git clone https://github.com/username/SCS_PoC.git
    ```

2. **Import Project into IDE**: Open the project in a Java Integrated Development Environment (IDE) such as IntelliJ IDEA or Eclipse.

3. **Run the Project**: Start the Smart Contract Server, then separately start the Node A and Node B clients.

4. **Follow the comments in the code for execution and communication**.

Thank you!
