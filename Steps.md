## Steps for unlocking

If you are have screen something like this, then follow the below mentioned steps:
<img width="644" height="462" alt="image" src="https://github.com/user-attachments/assets/1bb77bf8-745e-4714-9e80-b6789736f008" />


1. Start the recovery mode option -> Hold Shift and then press the restart button (make sure you are holding the shift button whole time till you press the restart), then you will see screen like this:
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/e5afeab1-bb38-4b7d-8cfe-96feb78a92d9" />

2. Click on the "Troubleshoot" option:
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/91ce9fd6-908b-4a96-b30d-eb2048999838" />

3. Then click on command prompt
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/a08cd476-e1f6-4628-842d-b32181e64962" />

4.Type the following command on the cmd: `regedit` (basically we are opening the registry editor applicaiton)
<img width="208" height="141" alt="image" src="https://github.com/user-attachments/assets/368b9e72-2a59-48f0-af19-b5e662ae87d9" />

5. Select the `HKEY_LOCAL_MACHINE` -> File Option -> Load Hive
<img width="445" height="282" alt="image" src="https://github.com/user-attachments/assets/f5d0e1c6-fb78-453a-8055-1c3f979ff7fa" />

6. Then navigate to the following location: `C:\Windows\System32\config` and locate the `SOFTWARE` file and click on open:
<img width="808" height="493" alt="image" src="https://github.com/user-attachments/assets/1e077b4c-57c9-4c67-9156-aef12413ead7" />

7. Then it will ask you to enter the key name, you can enter any key name that you want in my case I  entered `1234`
<img width="550" height="304" alt="image" src="https://github.com/user-attachments/assets/e1a343b6-889d-48e2-8206-1396c56d4f9e" />

8. After creating this entry you will see the name right below the `HKEY_LOCAL_MACHINE` entry,
<img width="1260" height="702" alt="image" src="https://github.com/user-attachments/assets/759a422d-b40a-4dac-aa2a-ceceb738f645" />

9. Expand the entry that have created, then follow the steps and open the following folder in it: **Microsoft** (Expand) ->  **Windows NT** (Expand) -> **Current Version** (Expand) -> **PasswordLess** (Expand) -> **Devices**

Or if you want to type the path it will look something like:
```
Computer\HKEY_LOCAL_MACHINE\1234\Microsoft\Windows NT\CurrentVersion\PasswordLess\Devices
```
10. Then click on the `Device Password Less Build Version` key -> and modify the `Value data` parameter with value `0` click Ok
<img width="979" height="278" alt="image" src="https://github.com/user-attachments/assets/60f5cc63-3795-41a7-9a53-0b0fa3c42d45" />

11. After that modify the key close everything and then click on the continue option
<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/fe4b2d19-5da8-4afd-8a20-3bd7138e5a07" />

12. Then you will see the `Sing-in options` click on it and enter your microsoft account password. 
<img width="96" height="79" alt="image" src="https://github.com/user-attachments/assets/00381dd6-4c7f-4146-aba7-b9a7c72f096f" />

And you are good to go!!
