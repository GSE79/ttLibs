# ttLibs
ttLibs are a platform for development of monitor & control ecosystems.  
-  Real-time embedded controllers without operating systems are developed from ttBareBones.
-  Real-time embedded controllers with operating systems are developed from ttOpSys.
-  Reliable tools and backend applications for PCs and Servers also are developed from ttOpSys.
-  Robust User Interfaces are developed from ttOpSys_Ubuntu_Qt, ttOpSys_WIN32_VS, and ttDotNet.

ttLibs are fully contained in a single repository to be forked, copied, subtree'd, submodule'd, or otherwise used to create custom product solutions.

Controllers, IoT Gateways, Data Acquisition Servers - all developed from common technology have gauranteed performance and the ability to communicate with common data models to connected memebers of the ecosystem.  Libraries are hardware agnostic allowing for execution on any processor with a c/c++ compiler.  Connections are HW agnostic allowing for communication over any interface and protocol.  
  
# ttBareBones
Source, Libs, and Example Applictions for uC based products with no operating system.  

Adherence to basic ttControls controls concepts gaurantees real-time performance and strategic connectivity of the ecosystem.  Abstraction from all standard library and procoessor specific code makes this library truely cross-platform and portable, even on proprietary uC hardware using proprietary compiler tools.  Floating point support augments available features but is not strictly required for use. 

# ttOpSys
Source, Libs, and Example Applications for uC, PC, and Server based products with an operating system.

ttOpSys extends the ttBareBones library with features like:
-  Services
-  File Systems
-  Inter-process communication
-  Networking
-  Threads
-  and Web User-Interfaces

ttOpSys depends on Standard Libraries, un-like ttBareBones.

# ttBareBones_Renesas_RX26T
Source, Libs, and Example Applications for Renesas RX26T uC.

# ttOpSys_rPi
Source, Libs, and Example Applications for Raspberry Pi.

# ttOpSys_Ubuntu_Qt
Source, Libs, and Example Applications developed and running on Ubuntu Linux using the Qt Creator IDE.

# ttOpSys_WIN32_VS
Source, Libs, and Example Applications developed and running on WIN32 Windows using the Visual Studio IDE.

# ttDotNet
Source, Libs, and Example Applications developed and running on .NET Windows using the Visual Studio IDE.
