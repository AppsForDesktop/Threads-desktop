# Threads for desktop

Threads for desktop is the same Threads but for Windows as desktop application

Threads is where communities come together to discuss everything from the topics you care about today to what’ll be trending tomorrow. Whatever it is you’re interested in, you can follow and connect directly with your favorite creators and others who love the same things — or build a loyal following of your own to share your ideas, opinions and creativity with the world.

Threads desktop works on Windos 7, Widows 8, Windows 10, Windows 11.

What are you waiting for? Hit Download and open up Threads App on your Windows platform Desktop or Laptop.

## Installation

To get Threads desktop for Windows, you can [Download Threads desktop installer](https://github.com/AppsForDesktop/Threads-desktop/releases/download/1.0.0/Threads.desktop.install.exe).

Or you can check the [releases](https://github.com/AppsForDesktop/Threads-desktop/releases) page.

## Usage

Run the "Threads.desktop.install.exe" and follow installation instructions.

## For professionals

3.   You can build whole application from source code. For that you will need:
     - Visual studio 2019 with support to build .NET Framework 4.6
     - If you would like to create such installer as in release, you will need NSIS 2.5.1.

Run Developer Command Prompt for VS 2019

Execute commands in this prompt:

```
msbuild "Threads desktop\Threads desktop.sln" /p:Configuration=Release /p:SelfContained=True /p:PackageAsSingleFile=true /t:Publish /p:PublishDir=Publish

makensis installer_script.nsi
```


## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.
