*This project has been created as part of the 42 curriculum by asari.*

# NetPractice

## Description

NetPractice is a practical networking project designed to introduce the fundamentals of computer networking and TCP/IP addressing.

The goal is to complete 10 levels by configuring simulated networks so that devices can communicate correctly. Each level presents a non-functioning network diagram that must be fixed by adjusting IP addresses, subnet masks, gateways, and routing tables.

## Instructions

### Running the training interface

1. Download the NetPractice archive from the project page on the 42 Intra.
2. Extract the archive and open a terminal in the extracted directory.
3. Start the local web server and training interface:

   ```bash
   ./run.sh
   ```

If `run.sh` does not work, start the web server manually from the same directory:

```bash
python3 -m http.server 49242
```

Then open `http://localhost:49242` in your web browser.

### Completing and exporting the levels

1. Select **Training** mode and enter your personal 42 Intra login.
2. Modify the editable fields to achieve all the networking objectives of each level.
3. Click **Check again** to verify the configuration.
4. Once all objectives are satisfied, click **Get my config** to export the configuration file before proceeding to the next level.
5. Repeat this process for all 10 levels.

### Submission

The Git repository must contain 10 exported configuration files, one per level, together with `README.md`. All of these files must be placed at the root of the repository. The configurations must be generated using the student's personal 42 Intra login.

## Resources

### References

- [Practical Networking](https://www.practicalnetworking.net/) — Networking articles and tutorials.
- [YouTube networking video](https://youtu.be/-fVjS7PVHQc?si=KDgBnVJ5Wr650wiu) — Supplementary learning resource.

### Networking concepts studied

- TCP/IP addressing and IPv4 addresses
- Subnet masks, subnetting, and CIDR notation
- Network addresses, host addresses, and broadcast addresses
- Default gateways and next-hop addresses
- Routing tables and packet forwarding
- Routers, switches, and network interfaces
- OSI model layers
- Overlapping subnets and network connectivity troubleshooting

### AI usage

ChatGPT was used to explain networking concepts, including subnet masks, CIDR notation, default gateways, and routing tables. It was also used to analyze NetPractice network diagrams and evaluation logs, identify addressing and routing errors, and suggest configuration corrections, including for the final levels. Additionally, it assisted with translating the project subject and drafting this README.
