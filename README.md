*This project has been created as part of the 42 curriculum by kuyu.*

# NetPractice

## Description

NetPractice is a networking project from the 42 curriculum designed to introduce and reinforce fundamental concepts of computer networking. The project is based on an interactive training interface where users solve a series of network configuration exercises.

The primary goal is to understand how devices communicate within a network by correctly configuring IP addresses, subnet masks, and routing rules. Each level presents a different scenario involving hosts, routers, and the internet, requiring logical reasoning to establish proper connectivity.

Through this project, the following core concepts are explored:
- IPv4 addressing
- Subnetting and subnet masks
- Default gateways
- Routing tables
- Communication between hosts and routers

---

## Instructions

### Running the Training Interface

To start the NetPractice interface, navigate to the project folder and run:

```bash
./run.sh
```

If the script is not executable, you can make it executable with:

```bash
chmod +x run.sh
```

This will launch the interactive training interface in your browser. 

### Solving Levels

- Each level presents a network topology with misconfigured or missing parameters.
- Your task is to assign correct IP addresses, subnet masks, and routes.
- Once the configuration is correct, the level will validate successfully.

### Exporting Configurations

After solving a level, you must export your configuration:

- Use the “Export” button in the interface
- This will generate a ``.txt`` file containing your network configuration

### Submission Requirements

- You must export 10 configuration files (one per level)
- Place all exported ``.txt`` files at the root of your repository
- File names should follow the expected format (e.g., ``level1.txt``, ``level2.txt``, ..., ``level10.txt``)

---

## Resources

### Networking Concepts Studied

This project covers essential networking concepts, including:

- TCP/IP addressing
- Subnet masks and CIDR notation
- Default gateways
- Routing tables and packet forwarding
- Routers and switches
- OSI model layers (especially Layer 3 – Network Layer)
- Basic network troubleshooting logic

### References
- [RFC 791 - Internet Protocol](https://datatracker.ietf.org/doc/html/rfc791)
- [RFC 950 - Subnetting](https://datatracker.ietf.org/doc/html/rfc950)
- https://www.cloudflare.com/learning/network-layer/what-is-an-ip-address/
- https://www.geeksforgeeks.org/computer-network-tutorials/
- https://subnettingpractice.com/


### AI Usage

AI tools (such as ChatGPT) were used in this project for:

- Understanding networking concepts (e.g., subnetting, routing logic)
- Clarifying exercise requirements and expected behaviors
- Reviewing and validating configuration logic
- Assisting in writing documentation (README structure and clarity)

AI was not used to directly solve levels automatically, but rather as a learning aid to improve understanding and problem-solving skills.

### Additional Notes

- This project is purely educational and focuses on conceptual understanding rather than implementation.
- No source code is required; only correct configurations are evaluated.
- Logical reasoning is essential for solving higher-level scenarios involving multiple routers and subnets.

---

### Author

kuyu