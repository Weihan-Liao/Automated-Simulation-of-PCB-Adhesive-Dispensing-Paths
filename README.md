# Automated-Simulation-of-PCB-Adhesive-Dispensing-Paths

This project utilized Pegatron Corporation's EasyCoat® software to assist Gap Filling machines (adhesive dispensing machines) in simulating adhesive dispensing paths on PCB boards before the actual dispensing process. By simulating predefined paths, combined with fixtures that shield areas unsuitable for dispensing, the adhesive process can be optimized.

For path recording, we used Excel to edit and document the point data of each path, including starting points, turning vertices, and endpoints. After completing the data editing, we developed a Python script to convert the point data in Excel into a binary file in TXT format using ASCII code. Subsequently, another program was used to convert the TXT file into an ECW file, which is the format supported by EasyCoat® for reading path data.

The research results simulated on the software showed that the path coordinates perfectly matched the initially defined vertex plans, successfully simulating adhesive dispensing paths on PCB boards while avoiding obstructions on the printed circuit boards.
