# Windows Installation

This guide provides instructions for installing Golang on Windows.

## Steps

1. **Download Go:**

   - Navigate to the [Go installation website](https://golang.org/dl/).
   - Download the latest 64-bit version of Go for Windows.

2. **Install Go:**

   - Run the downloaded MSI file.
   - Follow the installation prompts.
   - By default, Go is installed in `Program Files` or `Program Files (x86)`.

3. **Verify Installation:**

   - Open Command Prompt.
   - Type `go version` and press Enter.
   - Ensure the output shows the installed Go version.

4. **Set Up Workspace:**

   - Create a new folder for your Go projects (e.g., `C:\GoProjects`).
   - Inside this folder, create three subfolders: `bin`, `pkg`, `src`.

5. **Configure GOPATH:**

   - Go to Control Panel > System > Advanced system settings > Environmental Variables.
   - Under System Variables, click New and add `GOPATH` pointing to your Go workspace.

6. **Update System Path:**
   - Ensure `C:\Go\bin` is included in your system's Path variable.

## Troubleshooting

For installation issues, verify the environment variable settings and restart your system. For more help, visit the [Go installation documentation](https://go.dev/doc/install).
