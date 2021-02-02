# powershell-doc



## Process

### Get Process By Port Number
`Get-Process -Id (Get-NetTCPConnection -LocalPort YourPortNumberHere).OwningProcess`

### Stop Process
`stop-process [process id]`
