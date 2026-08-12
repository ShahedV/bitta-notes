## Installation
	sudo apt-get update
	sudo apt-get install -y dotnet-sdk-10.0
	dotnet new install Avalonia.Templates
	
## VS Code
	C# Dev Kit
	C#

## Project 
	dotnet new console -n HelloWorld
	dotnet run
	dotnet new avalonia.app -n ModerateUIApp
	dotnet build 2>&1 | grep -i "axaml\|error"
	dotnet publish -c Release -r win-x64 --self-contained true
This is Bitta Version