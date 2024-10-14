# eisenhower personal organizer AES 
Eisenhower Personal Organizer v 3.2 AES


This is the AES Version. use the launcher and enter a pass, the data and backup file will decrypt on launch and encrypt on exit.
To provide some level of Transparency for audit reasons, the AES encryption method can be viewed by accessing the two python scripts.
If you prefer AES with simultaneous backup functionality, an example (locksoft-backups) has been provided in the source code folder.

Please note, the compiled exe was provided for demonstration purposes and has strict data security. It uses two python scripts, the data hence could become inaccessible when incorrect passwords are used, backup copies are however kept. 
Adjust the code and recompile to create a less strict environment or use the provided script in the sourcefolder, in case you prefer to work with  backups while using AES. 

In order to exit while retaining your encrypted state, use the exit option from the menu. Otherwise your data could save without encryption.

 Installation: compile the source into your own exe using pyinstaller --onefile --windowed  source.py
 or use the exe from the repository
 Add some data to Brain Dump and restart the program to get your workflow going.


(c) Peter De Ceuster 2024
Software Distribution Notice: https://peterdeceuster.uk/doc/code-terms 
This software is released under the FPA General Code License.
 
   
 virustotal for the exe: MD5 7adf6231368637966f72510bbce44b38
 (5 false positives and 65 passed)
https://www.virustotal.com/gui/file/2cfb501d9dddf06ac58e65767339d0dfc53183bbd80cbbf02c83926ad7bef0a8/details
 
 
 
 
 
 
 
 
  