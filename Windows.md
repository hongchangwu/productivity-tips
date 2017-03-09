# PowerShell

## Enable running PowerShell scripts:

```powershell
Set-ExecutionPolicy RemoteSigned
```
## Profiles

To display the path to the profile

```powershell
$profile
```

To test if the the profile exists

```powershell
test-path $profile
```

To create a profile

```powershell
new-item -path $profile -itemtype file -force
```

The open the profile

```powershell
notepad $profile
```
