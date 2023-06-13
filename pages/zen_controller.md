## Zen Controller: Automation software for Zeiss Confocal Microscopes

<img src="https://github.com/bacorliss/zeiss_zen_controller/blob/d9da3b793d462ab42b8e16c9df23ac358102be1c/media/zen_controller_logo.png?raw=TRUE"/>
<br><br>
### A TCP/IP Programmatic Automation Interface for Zeiss Zen Confocal Laser Scanning Microscope Systems.


**Project description:** During my work in the crop biotech industry, I developed a software plug-in to automate the Zeiss Confocal Microscope at the Benfy Lab at Duke University as an independent consultant. The Zen Controller macro provides a real time automation interface for the Zen application (2009 SP1) that is operating system and network location independent. It designed with the intent of being an alternative or replacement for the Multitime macro by offering greater flexibility, stability, and speed when automating the microscope. With Multitime, users are restricted to using coordinate lists paired with specific imaging configurations. No changes can be made on the fly to the image settings, and imaging with Multitime is often slow between locations and time points. Zen Controller allows live changes to the microscope and executes commands in Zen as fast as a user can complete them manually. This speed is accomplished by designing the macro to be lightweight, with each command mimicking the same behavior as when the user makes a change within Zen. Its lightweight design also keeps the program stable for long experiments that demand continuous automation for days at a time. Currently, users can change critical settings on the fly like channel gain, AOTF, pinhole diameter, total z stack slices, and z stack spacing by sending simple text commands to the macro. The current list and syntax for commands is found in the wiki link. By closely following the structure and terminology in Zen, even non-technical users can understand the syntax and successfully write commands for the microscope after a cursory introduction.

<img src="https://github.com/bacorliss/zeiss_zen_controller/blob/d9da3b793d462ab42b8e16c9df23ac358102be1c/media/zen_controller_screenshot.png?raw=TRUE"/>
<br><br>
Zen Controller is designed to execute live commands sent from an external program residing on the same local computer, local network, or across the internet. The method of communication used is simple text messages sent with the TCP/IP protocol, which is one of the major protocols of the Internet protocol suite and is supported across all prominent programming languages. The macro acts as a TCP server and listens for text sent by a TCP client (in this case the program that is trying to automate the microscope). When a command or a series of commands are received, it starts to immediately execute them within Zen and sends the client status updates on whether each command succeeded. To start the automation, the user simply presses the start button and the macro begins to listen for incoming commands. The other window, titled “Zen Controller Debug Client”, is an example program written in Python where a user can type in commands, send them to the macro, and watch them be completed in Zen in real time. This program could be run just as easily from another computer and operating system, or written in any computer programming language.
<br><br>
<img src="https://github.com/bacorliss/zeiss_zen_controller/blob/d9da3b793d462ab42b8e16c9df23ac358102be1c/media/python_debug_client.png?raw=TRUE"/>
<br><br>

###Supported Systems
Zeiss CLSM 510 META, Zen 2009 V5.5 SP1
Zeiss CLSM PASCAL, Zen 2009 V5.5 SP1

**Github Repository:** <br>
[https://github.com/uva-peirce-cottler-lab/public_REAVER/issues](https://github.com/uva-peirce-cottler-lab/public_REAVER/issues)
<br><br>

------
