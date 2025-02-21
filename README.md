<h1>Local Attacks on DNS Server.</h1>

<h2>Description</h2>
The Domain Name System (DNS) functions as the Internet’s phone book, translating hostnames into IP addresses and vice versa. This translation process, known as DNS resolution, occurs behind the scenes. DNS attacks exploit vulnerabilities in this resolution process to redirect users to unintended, often malicious, destinations. The goal of this lab is to explore how these attacks operate. Participants will begin by setting up and configuring a DNS server, followed by executing various DNS attacks within a controlled lab environment to understand their impact and mechanisms.
<br />

![image](https://github.com/user-attachments/assets/af85632f-4ce9-447a-9585-808c59a1fe82)


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Ununtu 20.04 VM</b>

<h2>Environments Used </h2>

- <b>Windows 11 Home</b> (21H2)

<h2> Lab topics covered</h2>

- <b>DNS server setup</b>
- <b>DNS cache poisoning attack</b>
- <b>Spoofing DNS responses</b>
- <b>Packet sniffing and spoofing< /b>
- <b>The Scapy tool</b>


<h2>Shell scripts commands</h2>

- `./dc-build.sh` - Build the docker images, it can take one additional parameter to be used in the build process, e.g. `./dc-build.sh --no-cache`.
- `./dc-up.sh` - Start the docker containers in the foreground.
- `./dc-up-d.sh` - Start the docker containers in the background.
- `./dc-stop.sh` - Stop the docker containers, it can take one additional parameter to be used in the stop process.
- `./dc-down.sh` - Stop and remove the docker containers, it can take one additional parameter to be used in the stop and remove process.
- `./dc-unittest.sh` - Utility script to aid in running a specific unit test class.

<h2>Program walk-through:</h2>

- <b> Using Scapy for Sniffing and Spoofing:</b>

     1. Task 1: Directly Spoofing Response to User<br>
     2. Task 2: DNS Cache Poisoning Attack – Spoofing Answers<br>
     3. Task 3: Spoofing NS Records<br>
     4. Task 4: Spoofing NS Records for Another Domain<br>
     5. Task 5: Spoofing Records in the Additional Section<br>
 


