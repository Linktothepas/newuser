Start-Process -FilePath "\\avs-ifs-01\logon\Software\ninja\ninja-main.msi"

Start-Process "outlook.exe"

Start-Process -FilePath "\\avs-ifs-01\Public\IT\Office\TeamsSetup_c_w_ (1).exe" -ArgumentList "/silent", "/install" -Wait

Start-Process -FilePath "\\avs-ifs-01\Public\IT\PDF-XCHANGE\PDFXVE9.exe" -ArgumentList "/silent", "/install" -wait

mstsc.exe /v:avs-its-01 /multimon /public
