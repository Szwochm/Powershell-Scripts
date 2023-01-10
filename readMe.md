# Open a new Powershell Window as Administrator in current working directory

Start-Process powershell -Verb runAs -WorkingDirectory (Get-Location)
