# How-to-Setup-Regedit-Editor-for-VPN-Purpose
Need to setup regedit before connect  vpn 

	In windows click on search bar
<img width="674" height="150" alt="image" src="https://github.com/user-attachments/assets/bf4c845b-0fd5-4b1f-8411-1f42d9d4ebc7" />
	Type On search bar Regedit 
<img width="849" height="446" alt="image" src="https://github.com/user-attachments/assets/0f768030-e697-4c52-a0d0-7adf00bb9e60" />

	Click in Computer
<img width="1125" height="359" alt="image" src="https://github.com/user-attachments/assets/09332bab-a59f-4c40-b386-0ca364b6e5f0" />

	Click in HKEY_LOCAL_MACHINE
<img width="1125" height="374" alt="image" src="https://github.com/user-attachments/assets/8373ab27-b6fc-43b5-ae57-37101448d50d" />

	Click in System
<img width="1020" height="719" alt="image" src="https://github.com/user-attachments/assets/05910ba3-c1f4-4898-a067-f0fb5f6af102" />
Click in currentcontrolset: 
<img width="915" height="708" alt="image" src="https://github.com/user-attachments/assets/27b5cdbd-a9ed-4512-b3d6-085fb4b902ac" />
Click in services:
<img width="1125" height="670" alt="image" src="https://github.com/user-attachments/assets/6ce9dd1f-2ea2-4b5f-839d-b64d5557e656" />

Right click on policy agent and select Doward 32bt:
<img width="1125" height="566" alt="image" src="https://github.com/user-attachments/assets/e06f7c28-4e6f-4e6a-a5df-43caa687ad84" />
Type Code: AssumeUDPEncapsulationConttextonSendRule
<img width="1125" height="619" alt="image" src="https://github.com/user-attachments/assets/a7183543-258e-4f78-969f-0d2209b87787" />

Double Click on Assume code and put 2:
<img width="1125" height="565" alt="image" src="https://github.com/user-attachments/assets/e860672e-e93b-43e1-94f8-3b61a300aff7" />

Then Ok and Restart Computer:
	Next step is to search bar and type VPN Setting:
<img width="1069" height="482" alt="image" src="https://github.com/user-attachments/assets/157f90fc-3798-4824-9fb0-929a23c17e82" />

Click in Add VPN:
<img width="1124" height="633" alt="image" src="https://github.com/user-attachments/assets/37d172c2-9c9d-4ed9-b352-55ce52ea3056" />

	After Add VPN Fill username, Passwords and Connection Name:
<img width="587" height="649" alt="image" src="https://github.com/user-attachments/assets/a6cde6df-6c85-4b1a-93aa-0006c323d590" />
	Pre-shared Key: provided by your company.
	Type of sign-in info: provided by your company
	Then Save
	Go to search for a bar and type ncp.cpl

<img width="788" height="533" alt="image" src="https://github.com/user-attachments/assets/95f482f8-c473-43e6-8489-accfa1cc95f4" />

Click in View Network connection:
<img width="1125" height="636" alt="image" src="https://github.com/user-attachments/assets/4b72f7a5-c546-43a5-b467-fae353aa26ad" />

	Right Click in eitvpn and go to Property:
<img width="1125" height="556" alt="image" src="https://github.com/user-attachments/assets/28732cce-105d-4597-89e6-fd8b9fdeea0e" />

	Click in security and choose to allow this protocol and click in Microsoft CHAP version 2 
<img width="615" height="500" alt="image" src="https://github.com/user-attachments/assets/43000090-350f-4702-892d-8a26cf0ad308" />

	Click in Networking choose protocol version 4 
<img width="685" height="208" alt="image" src="https://github.com/user-attachments/assets/dd65678d-34a9-46e0-9e1b-0c907eebe5e5" />

	Then click in properties
<img width="709" height="442" alt="image" src="https://github.com/user-attachments/assets/e9326587-32fe-4590-b413-c3ea1a6433cf" />

	Then click in advance 
	Unclick default gateway and 
	choose automatic Metric then click ok

<img width="766" height="656" alt="image" src="https://github.com/user-attachments/assets/9272f586-2927-48e4-b02d-1d24e4943970" />

	Then ok 

