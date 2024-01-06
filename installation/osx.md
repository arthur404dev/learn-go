# macOS Installation 

This guide provides two methods for installing Golang on macOS: direct download and installation via Homebrew.

## Method 1: Direct Download

1. **Download Go:**

   - Visit the [official Go website](https://go.dev/doc/install) and download the latest version of Go for macOS.

2. **Install Go:**

   - Open the downloaded file.
   - Follow the prompts in the installation wizard to install Go on your system.

3. **Verify Installation:**

   - Open a terminal window.
   - Type `go version` and press Enter.
   - You should see the installed version of Go displayed.

4. **Set Up Your Workspace:**

   - Choose or create a directory where you will keep your Go code (e.g., `~/go`).
   - Set this directory as your workspace.

5. **Configure Environment Variables:**
   - Add the Go workspace's `bin` subdirectory to your `PATH`.
   - You can do this by adding `export PATH=$PATH:~/go/bin` to your `.bash_profile` or `.zshrc` file.

## Method 2: Installation via Homebrew

1. **Install Homebrew:**

   - If you don't have Homebrew installed, follow the [official Homebrew website installation steps](https://docs.brew.sh/) to install it.

2. **Install Go:**

   - After installing Homebrew, install Go by running `brew install go` in the terminal.

3. **Verify Installation:**
   - Type `go version` in the terminal to confirm the installation.

## Troubleshooting

If you encounter issues, verify that your `PATH` is set correctly and that you are using the latest version of Go. For more detailed troubleshooting, refer to the [Go installation documentation](https://go.dev/doc/install).
