INFORMATIONS ABOUT PLUGIN TEMPLATE 
(template by Vichingo455)
===========================================

Files:
template.ini - Plugin file
template_enable.bat - Enable plugin script
template_disable.bat - Disable plugin
                                          script
example.ini - Example of plugin

===========================================

PLUGIN TEMPLATE SECTIONS

INFO
Name: The name of the plugin
Description: A little text about what the 
                      plugin does
Author: The author of the plugin

TOGGLE
Enable: The plugin's enable command
Disable: The plugin's disable command

STATUS
Command: The command to determine if 
                   the plugin is enabled or not
Type: The type of the status command,
           output or code (code=error code)
Value: The value of the plugin if enabled
            (if you added a registry key DWORD,
             you usually have to set this value
             to 0x1)

===========================================
