# NVIDIA-Container-Integrity-LS
NvContainerLocalSystem Service made for machine integrity against general malicious behavior and processes.

This service \\ service process is based but not affiliated with that of NVIDIA's NVIDIA GeForceNOW 
NVIDIA Container LS service made to ensure integrity of vm-seats.

This service requires:
- .NET 4.8
- Windows 10 or Upwards

How to set it up:
- Launch Install.bat, and the service should be installed, and it should boot every system start.

How does it work?:
The service process upon starting up loads plugin's in the form of applications extensions (.dll)'s in a predefined directory else it shall make one, those plugins all have they're own job and task here's a list of them and they're acronyms explained:
- GciPlugin (GeForce Code-Integrity Plugin) >> Blocks malicious and unwanted software and anything of that nature.
- GssmPlugin (GeForce Session-Seatmonitoring Plugin) >> Blocks backdoors specifically and anything related.
- UadPlugin (Unauthorized Activity Detection Plugin) >> Blocks unauthorized activity (Networking mainly)
- LkmPlugin (Loadable Kernel Module Plugin) >> Ensures a safe shutdown of the service and ensures Drivers and stability of the system dont get compromised by denying permission to critical system files or directories.
  

Why did i create it?:
- Out of boredom and a quest to create useful software which can be used widespread for a good cause.

# Tags:
NVIDIA GeForce-NOW, GFN, GeForceNOW, GeforceExperience, GCIS.
