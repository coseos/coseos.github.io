
# Enable updates

Windows 7 SP1 (and Windows Server 2008 R2 SP1) do not include
any antivirus application. Microsoft will not install any
security updates starting January 2018 unless you install
some antivirus software or set the following registry key.

Start the registry editor (RegEdit.exe) and select

    HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\QualityCompat"

Change or set the entry *cadca5fe-87d3-4b96-b7fb-a231484277cc* to a
REG_DWORD value 0.

