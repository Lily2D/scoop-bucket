# Lily2D Scoop Bucket

[Scoop](https://scoop.sh/) bucket for [Lily2D](https://lily2d.com) Game Engine.

## Installation

1. Install Scoop

Open **PowerShell** and run:

```powershell
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
Invoke-RestMethod -Uri https://get.scoop.sh | Invoke-Expression
```

2. Add Lily2D Bucket URL (only needed first time)

Run the following command to add this repository to your Scoop installation:

```powershell
scoop bucket add lily https://github.com/lily2d/scoop-bucket
```

3. Install Lily2D

```powershell
scoop install lily
```

## Updating

To update lily console:

```powershell
scoop update lily
```
