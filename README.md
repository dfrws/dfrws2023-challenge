# <p style="text-align: center;"> DFRWS 2023 Challenge - The Troubled Elevator</p>
The DFRWS 2023 challenge (**The Troubled Elevator**)  takes a deep dive into the domain of Industrial Control Systems (ICS), specifically focusing on programmable logic controllers (PLC). These systems are increasingly critical in various sectors, such as energy, water, transportation, and manufacturing, monitoring and controlling industrial processes. This challenge aims to provide deeper insights into ICS network traffic analysis and device memory in a real-world scenario.

[![ICS Example](https://github.com/dndusdndus12/dfrws2023-challenge-img/blob/main/Figure1.jpg)](https://dfrws.org/forensic-challenges/)

The scenario for this challenge, "The Troubled Elevator," involves investigating a mysterious incident in a bank’s executive-only elevator. Participants with different technical skills in forensic investigations are encouraged in this competition, with opportunities for innovative investigative approaches in network, memory, and embedded systems.


## Scenario: The Troubled Elevator
Kristi Wayne from Wayne Enterprise has recently bought a controversial bank in the city of Richmond.
On June 29, Friday afternoon, during her visit to the bank, she used an executive-only elevator designed to provide a smooth and private commute for the high-ranking officials within the bank. Wayne enters the elevator and presses the button to get to another floor. However, the elevator suddenly starts malfunctioning, trapping Wayne inside. Wayne calls from the elevator for emergency assistance. After an extended episode of patience and misery, she is finally rescued. Due to this high-profile incident, your forensic team has been called for an investigation. Fortunately, the elevator infrastructure is designed to log network traffic and device memory dumps for a certain time period. You acquire them along with CCTV footage of the elevator and the memory dump of Wayne’s new computer in her office at the bank.

## Challenge
Your job is to investigate the entire incident and provide a comprehensive report, including:
- Elevator behaviors during malfunctioning
- Timeline of elevator malfunctioning
- Specific cause of malfunctioning
- Any evidence of an inside attacker
- Any attack evidence on the network, computer, and PLC device

## Evaluation Criterion
The team that covers the incident most comprehensively will win the challenge.

## Team Registration
Please register your team using the following Google form. We will use this information to contact the teams to provide relevant information as needed. Note that the team members in the form is not considered final and may change in the final submission.

Google Forms: https://forms.gle/f7S7yvQq5Lo6Msrj9

## Submission
Submission deadline: May 1, 2024

Submission Google Form: https://forms.gle/drLn7mkx5udmiio17


### Contact Information
ics@dfrws.org


### Challenge Organizer
Security and Forensics Engineering (SAFE) Lab at Virginia Commonwealth University (VCU), http://people.vcu.edu/~iahmed3/

**SAFE Lab Team:**

[![Photos](https://github.com/dndusdndus12/dfrws2023-challenge-img/blob/main/Photo.png)](http://people.vcu.edu/~iahmed3/)

- **Irfan Ahmed**, DFRWS Challenge Chair and Associate Professor at Virginia Commonwealth University
- **Wooyeon Jo**, Postdoctoral Research Fellow at Virginia Commonwealth University
- **Adeen Ayub**, PhD Candiate at Virginia Commonwealth University
- **Muhammad Haris Rais**, Former PhD Student and Alumnus of the SAFE Lab; now Assistant Professor at Virginia State University, VA
- **Hala Ali**, PhD Student at Virginia Commonwealth University
- **Nehal Ameen**, PhD Student at Virginia Commonwealth University
- **Muhammad Ahsan**, PhD Student at Virginia Commonwealth University
- **Syed Ali Qasim**, Former PhD Student and Alumnus of the SAFE Lab; now Assistant Professor at Grand Valley State University, MI



## Challenge Data
Please note, due to upload file size limitations, some files have been split into compressed segments. We recommend using below table to verify the integrity of the original files.

|No|Description | /Path/File | SHA256|
|:---| :---: | :---: | ---: |
|1|Manual for programming M221 PLC control logic in elevators|/Documents/Elevator Manual.pdf|083bf2f8e4f9b72fffc472650f0ba69979a003959a9c9bf984b4756b8583c266|
|2|Network diagram of the target network|/Documents/Network Diagrams.pdf|e674c32ea8a5348f02c9ea81b701f97b5b3f559b3f23c5562c9ee5889b41bbc9|
|3|Network Trace|/Network Trace/142728_162728.pcapng|3b42d8eca97a62cd3db5801100b4ba51954f3c0a261bbea92d0a567e1ef885c9|
|4|RAM Memory dump of CEO's desktop|/Desktop Memory Dump/DESKTOP-JKS05LO-20230622-143255.raw|c476d6beffde196ba185572dfe8b27aeff7c1de3095558c66539faf8dbc22c0f|
|5|PLC's external RAM image dump|/PLC Memory Dumps/ExtRAM_20230629143509.bin|ee0b4e0d06a0b4de753ed9bef4a873823ca7d091fbc052b1f9a7346093a46ae8|
|6|PLC's external RAM image dump|/PLC Memory Dumps/ExtRAM_20230629145014.bin|dda6f2b1d234e51cd6d180721415ff13928b8c81c2ae10b9aeee87addba8d282|
|7|PLC's external RAM image dump|/PLC Memory Dumps/ExtRAM_20230629150519.bin|de22844ad4f058e339472b372286a2a231af586ef264aa1e7681081e341ac3e4|
|8|PLC's on-chip RAM image dump|/PLC Memory Dumps/ExtRAM_20230629152024.bin|af16e1098e606cb04cd51de15f127bd2f7308026b7fb2da92798857dd50862e3|
|9|PLC's on-chip RAM image dump|/PLC Memory Dumps/ExtRAM_20230629153528.bin|20d564930367e5837dd964e3547f4ceb8d8da892bb539f38baa94cde9b0f0eba|
|10|PLC's on-chip RAM image dump|/PLC Memory Dumps/ExtRAM_20230629155033.bin|5a021c340ca0de429ef2be127ea97f07a3fd2909daf84d4bcbc4fa0ae1e2ada1|
|11|PLC's on-chip RAM image dump|/PLC Memory Dumps/ExtRAM_20230629160538.bin|3cb665761b0891f220a57ede0368b4dd331e7b811e27da9ae13081a5067091d0|
|12|PLC's on-chip RAM image dump|/PLC Memory Dumps/OnChipRAM_20230629143506.bin|82b77f3d6632047d5191c3bd0e2f6436996003ed0e99b521690d2894b75a1449|
|13|PLC's on-chip RAM image dump|/PLC Memory Dumps/OnChipRAM_20230629145007.bin|b7b4851e6de68c45d2ca0da8e67163cc2a3984c1026673adce21a01d7069c963|
|14|PLC's on-chip RAM image dump|/PLC Memory Dumps/OnChipRAM_20230629150509.bin|fc206163a0a762d5547106542b3c98c84f5a3e1f1eea0feb66d6686856731e7b|
|15|PLC's on-chip RAM image dump|/PLC Memory Dumps/OnChipRAM_20230629152010.bin|af3ebc6942c401a7f8a0de0124d99f3904ae9789f694a0ca9541ffd8cfff8090|
|16|PLC's on-chip RAM image dump|/PLC Memory Dumps/OnChipRAM_20230629153511.bin|9a59e608d9d77678e46d0bc9f176f2ea093fecb7bcf0859a767e37c80b1a00b1|
|17|PLC's on-chip RAM image dump|/PLC Memory Dumps/OnChipRAM_20230629155012.bin|3d484e21654e6e04a6f3d4a94515cc6a8321435ee18322958daf09111d0e428f|
|18|PLC's on-chip RAM image dump|/PLC Memory Dumps/OnChipRAM_20230629160514.bin|ca99a13963f5ad66d2b36dbb947719da60654a083bbda549d25107aa339de684|
|19|CCTV Footage|/CCTV Footage/Crop_fit.mp4|a036e61586898c77092cfc8aeb9966ccc1b8ade3c94cd147665090be75978b5d|
