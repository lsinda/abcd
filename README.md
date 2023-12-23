# abcdSet WshShell=WScript.CreateObject("WScript.Shell")
WshShell.AppActivate"None"
for i=1 to 1000
WScript.Sleep 1
WshShell.SendKeys"^v"
WshShell.SendKeys i2
WshShell.SendKeys"%s"
Next
