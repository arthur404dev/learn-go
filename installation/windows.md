# Windows Installation

> Note for Windows Users with WSL/WSL2
> If you are using Windows Subsystem for Linux (WSL) or WSL2, follow the Linux installation steps as WSL/WSL2 allows you to run a Linux environment directly on Windows.

1. **Install Git:** Go often uses open-source repositories, so it's recommended to install Git first. You can download it from the [Git website](https://git-scm.com/).

2. **Download Go:** Navigate to the [Go installation website](https://go.dev/doc/install) and download the latest Go version for Windows.

3. **Run the Installer:** Follow the instructions in the Go installation program.

4. **Verify Installation:** Open Command Prompt and type `go version` to check if Go is installed correctly.

5. **Set Up Workspace:**

   - Go to Control Panel > System and Security > System > Advanced system settings.
   - Click on Environmental Variables and ensure `C:\Go\bin` is included in the Path under System Variables.
   - Create a Go workspace in a new folder, separate from where Go installation files are saved, for example, `C:\Projects\Go`.
   - Inside your Go workspace, set up three new folders: `bin`, `pkg`, `src`.

6. **Create GOPATH Variable:** In Environmental Variables, under System Variables, click on New. Enter `“GOPATH”` as the Variable Name, and the path to your Go workspace (e.g., `C:\Projects\Go`) as the Variable Value.

7. **Test Installation:** Open Command Prompt and type `go get github.com/golang/example/hello`. Then run `%GOPATH%/bin/hello`. You should see a message like:

```
"Hello, Go examples!"
```