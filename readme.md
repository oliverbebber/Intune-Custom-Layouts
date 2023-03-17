# Intune Custom Layouts

This project is a work in progress as I deploy custom layouts for endpoints. 

Note: The following information applies to Windows 10.

- Start Menu Layout
- Task Bar Layout

In order to deploy these customizations, you will need to have **one** XML file. 

- Intune doesn't allow the use of two XML files for the same policy.


# Start Menu Layouts

There are two types of Start layouts that can be used.

Full Start Layout

- Does not allow users to pin, unpin, or uninstall apps from Start.
- Users **can** view and open all apps in the All Apps view

Partial Start Layout

Note: This is only supported on Windows 10, version 1511 and later.

- Tile groups and the contents cannot be changed, however, users **can** move these groups.
- Users **can** also create and customize their own tile groups.

# Task Bar Layouts




# Resources

Start Menu Layouts: 

- https://learn.microsoft.com/en-us/windows/configuration/customize-and-export-start-layout

Export-StartLayout PowerShell cmdlet:

- https://learn.microsoft.com/en-us/powershell/module/startlayout/export-startlayout?view=windowsserver2022-ps

Customize Start & Taskbar with MDM:

- https://learn.microsoft.com/en-us/windows/configuration/customize-windows-10-start-screens-by-using-mobile-device-management