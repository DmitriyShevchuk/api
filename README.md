# Install

<details>
<summary>Windows</summary>
 
### Stage 1: Install choco
```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
### Stage 2: Install dependencies
```powershell
choco install php --version=8.1.27
``` 
```powershell
choco install symfony-cli
``` 
```powershell
choco install composer
``` 
```powershell
choco install postman
``` 

### Stage 3: Clone repository
```git
git clone https://github.com/DmitriyShevchuk/api.git
```

### Stage 4: Install composser dependencies
```powershell
cd api
```
```powershell
composer install
```

### Stage 5: Start server
```powershell
symfony serve
```

</details>

<details>
<summary>Linux</summary>

```powershell
❌ Error: Download windows 
```
</details>

# Documentation
❤️ [Click me]([https://web.postman.co/documentation/41672010-f9e06b63-dc5b-45a0-a729-e8ab3ec572ae/publish?workspaceId=7c512977-b2ef-4bf0-8569-9c1e7382f215](https://documenter.getpostman.com/view/41672010/2sAYX3rNsi))
