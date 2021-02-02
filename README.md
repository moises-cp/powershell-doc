# powershell-doc



## Process

### Get Process By Port Number
`Get-Process -Id (Get-NetTCPConnection -LocalPort [port number]).OwningProcess`

### Stop Process
`stop-process [process id]`
