winget install -e --id Microsoft.Office

Start-Process -FilePath "\\avs-ifs-01\Public\IT\Office\TeamsSetup_c_w_ (1).exe" -ArgumentList "/silent", "/install" -Wait

winget install -e --id TrackerSoftware.PDF-XChangeEditor

mstsc.exe /v:avs-its-01 /multimon /public
