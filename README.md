When running discovery on a Windows server, the RAM value is retrieved from the registry. However, this value may not reflect any recent increase in RAM on the machine. To fetch the updated RAM value, you can use the following command in the Command Prompt.

“wmic computersystem get totalphysicalmemory”

I have incorporated this feature into the extension step of the Windows discovery pattern. Please find the attachment accompanying this article for more details.
