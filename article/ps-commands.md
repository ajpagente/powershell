# Useful Powershell Commands

## Determine Powershell version
"""
$PSVersionTable
"""

## Enable running scripts
By default, Powershell script execution is disabled. This is a security measure to prevent accidentally executing malicious scripts.

To be able to run the following activation/deactivation commands, run Powershell as Administrator.

### Check execution policy
"""
$Get-ExecutionPolicy
"""

### Enable script execution
"""
$Set-ExecutionPolicy Unrestricted
"""

### Disable script execution
After running your script you may want to disable script execution as a security practice.
"""
$Set-ExecutionPolicy Restricted
"""
