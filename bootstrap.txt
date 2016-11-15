#iwr https://chocolatey.org/install.ps1 -UseBasicParsing | iex

choco install git -y
choco install github -y
choco install telegram.install -y
choco install sourcetree -y
choco install awscli -y
choco install adobereader -y
choco install vlc -y
choco install putty -y
choco install vagrant -y
choco install packer -y
choco install docker-machine -y

Install-PackageProvider -Name NuGet -Verbose -Force
Install-Module -Name AWSPowerShell -Verbose
Install-Module -Name AzureRM -Verbose
Install-Module -Name IseSteroids -Verbose
Install-Module -Name Posh-Git -Verbose