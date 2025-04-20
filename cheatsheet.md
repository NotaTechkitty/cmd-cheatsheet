/******\******* ✨ Check internet profile ⭐ ******\*******/

### Command: `netsh wlan show profile name="Wi-Fi Name" key=clear`

This command is used to display detailed information about a specific Wi-Fi profile on a Windows machine, including the security key (password) in clear text.

#### Parameters:

- `name="Wi-Fi Name"`: Specifies the name of the Wi-Fi profile you want to display. Replace `"Wi-Fi Name"` with the actual name of your Wi-Fi network.
- `key=clear`: Instructs the command to show the security key (password) of the Wi-Fi profile in plain text.

#### Usage:

Run this command in Command Prompt with administrative privileges to view the details and password of a saved Wi-Fi profile.

#### Example:

```sh
netsh wlan show profile name="HomeNetwork" key=clear
```

This will display the configuration details of the "HomeNetwork" profile, including the password if available.

#### Notes:

- Ensure you have administrative rights to execute this command.
- Revealing passwords in plain text can pose a security risk; use with caution.

/******\******* Check internet profile ******\*******/
