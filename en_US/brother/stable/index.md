# Brother

Plugin gathering information from your network connected Brother printer using SNMP protocol.

Several commands are availale like the different ink/toner levels.

>**Important**
>You printer must be:
- a Brother one :)
- connected to your local network
- have SNMP enabled (you might need to go to your printer's interface to enable it)

# Configuration

## Plugin configuration

The plugin **Brother** does not require any specific configuration and should only be activated after installation.

## Equipment configuration

To access the different equipment **Brother**, go to the menu **Plugins → Monitoring → Brother**.

> **To know**
> The button **+ Add** allows you to add a printer **Brother**.

On the equipment page, fill in the **hostname or IP address** of your printer and select its **type**, then click on the button **Save**.

A widget's template is available. To use it, click the checkbox.

# Remarks

Most probably, some Brother printers might not be compatible. Just try and see!

# Contributions

This plugin is opened for contributions and even encouraged! Please submit your pull requests for improvements/fixes on <a href="https://github.com/badwolf42/plugin-brother/issues" target="_blank">Github</a>

# Credits

This plugin relies on the work done by:
- [hugoKs3](https://github.com/hugoKs3) who created this plugin in February 2022 and maintained it until January 2023
- [bieniu](https://github.com/bieniu) for the Python package [brother](https://github.com/bieniu/brother)
- [Nebz](https://github.com/NebzHB) for the package [dependance.lib](https://github.com/NebzHB/dependance.lib)
- [Mips](https://github.com/Mips2648) for the package [pyenv.lib](https://github.com/NebzHB/dependance.lib/blob/master/pyenv.md) and the GitHub workflow [plugins-translations](https://github.com/Mips2648/plugins-translations)

# Disclaimer

- This code does not pretend to be bug-free
- Although it should not harm your Jeedom system, it is provided without any warranty or liability

# ChangeLog
Available [here](./changelog.html).
