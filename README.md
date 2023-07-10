# aspx-reverse-shell
Aspx reverse shell

ASPX Reverse Shell is an ASP.NET page written in C# that provides reverse shell/bind shell functionality. It allows the execution of commands on a remote server.

### Prerequisites

- ASP.NET environment
- Windows operating system

### Usage for the original InsomniaShell

1. Download the InsomniaShell.zip file from the [original shell post](https://www.darknet.org.uk/2014/12/insomniashell-asp-net-reverse-shell-bind-shell/) or [this link](https://www.darknet.org.uk/content/files/InsomniaShell.zip).

2. Extract the contents of the ZIP file.

3. Open the InsomniaShell.aspx file in a text editor.

4. Modify the `host` and `port` variables in the `Page_Load` method according to your target server.

5. Deploy the ASP.NET page to your web server or run it locally.

6. Access the InsomniaShell page using a web browser.

7. The page will establish a connection to the specified server and port, send a request, and execute the provided commands on the remote server.

### Notes

- The code uses various C# structures and methods to interact with the Windows API, including functions from DLLs such as kernel32.dll, ws2_32.dll, advapi32.dll, and psapi.dll.

- The functionality of the code depends on the proper configuration of the ASP.NET environment and the system where it is deployed.

- Use this code responsibly and only on systems that you have authorized access to.

### Disclaimer

The InsomniaShell code is provided for educational purposes only. The authors and contributors are not responsible for any misuse or illegal activities conducted with this code.
