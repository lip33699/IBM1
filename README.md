twsinst.vbs -new -skipcheckprereq `
  -uname CAA01100svczc1 `
  -password ****** `
  -acceptlicense yes `
  -adjruntime false `
  -hostname $env:COMPUTERNAME `
  -displayname $env:COMPUTERNAME `
  -jimport 5010 `
  -jimportssl false `
  -inst_dir "D:\apps\IBM\TWA" `
  -Wait -PassThru `
  -NoNewWindow `
  -RedirectStandardOutput "D:\apps\IBM\TWA\Logs\twa.log" `
  -RedirectStandardError "D:\apps\IBM\TWA\Logs\twa_error.log"

