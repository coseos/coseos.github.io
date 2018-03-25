
# Disable UAC

To disable UAC in Windows, use the registry editor (RegEdit).

Select

    HKEY_LOCAL_MACHINe\Software\Microsoft\Windows\CurrentVersion\Policies\System

You should find a REG_DWORD entry *EnableLUA* and set this value to 0.

You can also supress the consent dialog for UAC in the registry. Set
the value for *ConsentPromptBehaviorAdmin to 0.

You need to restart your computer to make changes take effect.

