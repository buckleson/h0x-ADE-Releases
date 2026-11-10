<p align="center">
  <img src="assets/hyperox.png" alt="HyperOx" width="120">
</p>

<h1 align="center">HyperOx</h1>

<p align="center">
  <b>The desktop workspace for AI coding agents.</b><br>
  Run Claude Code, Codex, Gemini, OpenCode and your own tools side by side, watch what every agent is doing, and stay in control from your desk or your phone.
</p>

<p align="center">
  <a href="https://github.com/buckleson/h0x-ADE-Releases/releases/latest/download/h0x-ade-windows-x86_64.tar.gz"><img alt="Download for Windows" src="https://img.shields.io/badge/Download-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>
  <a href="https://github.com/buckleson/h0x-ADE-Releases/releases/latest/download/h0x-ade-macos-aarch64.tar.gz"><img alt="Download for macOS" src="https://img.shields.io/badge/Download-macOS%20(Apple%20Silicon)-000000?style=for-the-badge&logo=apple&logoColor=white"></a>
  <a href="https://github.com/buckleson/h0x-ADE-Releases/releases/latest/download/h0x-ade-linux-x86_64.tar.gz"><img alt="Download for Linux" src="https://img.shields.io/badge/Download-Linux%20x86--64-FCC624?style=for-the-badge&logo=linux&logoColor=black"></a>
  <a href="https://github.com/buckleson/h0x-ADE-Releases/releases/latest/download/h0x-ade-linux-aarch64.tar.gz"><img alt="Download for Linux ARM" src="https://img.shields.io/badge/Download-Linux%20ARM64-FCC624?style=for-the-badge&logo=linux&logoColor=black"></a>
</p>

<p align="center">
  <a href="https://www.pavii.tech/products/dev-tools/docs/"><b>Documentation</b></a> ·
  <a href="https://pavii.tech"><b>Pavii</b></a> ·
  <a href="https://buckleson.com"><b>Buckleson</b></a> ·
  <a href="https://github.com/buckleson/h0x-ADE-Releases/releases"><b>All releases</b></a>
</p>

---

## What is HyperOx?

HyperOx is a desktop app for working with AI coding agents. Every agent gets its own terminal, and HyperOx keeps track of all of them: which one is working, which one is waiting for you, and which one is done. You spend less time switching windows and more time shipping.

- **Many agents, one window.** Open as many agent terminals as you like, arrange them in tabs and layouts, and save the layout for next time.
- **Know what each agent is doing.** Every terminal shows a clear status (working, waiting for you, done, error), so you can see at a glance where you are needed.
- **Never lose a session.** Terminals keep running in the background engine even when the window is closed, and they come back exactly where you left them.
- **Control from anywhere.** Pair your phone or Telegram to see your agents, get a notice when one finishes, and answer permission prompts while you are away from your desk.
- **Work on other machines.** Connect to your servers over SSH and run agents there as if they were local.
- **Make it yours.** Layouts, settings and mods let you shape the workspace around how you work.
- **Built to be safe.** Every download and update is signed and checked before it installs, and HyperOx collects no usage data.

## Download and install

1. Click the download button for your computer at the top of this page. It always gives you the newest version.
2. Unpack the file:
   - **Windows:** right-click the downloaded file and choose **Extract All**, or use 7-Zip.
   - **macOS and Linux:** double-click the file, or run `tar -xzf` on it in a terminal.
3. Open **HyperOx** (`h0x-ade`) from the unpacked folder.
4. On the first start, HyperOx sets up its background engine for you. There is nothing else to install.

Older versions and the release notes for each version are on the [releases page](https://github.com/buckleson/h0x-ADE-Releases/releases).

## Updates

HyperOx tells you when a new version is ready and installs it when you say so. You can turn the update check off in **Settings**.

## How it works

HyperOx has two parts that work together:

- **The app** is the window you see: tabs, layouts, agent status, settings and mods.
- **The engine** runs quietly in the background and keeps every terminal alive, even when the app is closed. It also powers phone and Telegram control and connections to other machines.

Because the engine owns the terminals, you can close or restart the app and your agents keep working.

## Safe by design

- Every release file is signed. HyperOx checks the signature before it installs or updates anything, and refuses a file that does not match.
- Downloads come only from the official HyperOx release pages, over a secure connection.
- No telemetry. HyperOx does not collect or send usage data. The only automatic network request is the update check, and you can turn it off.
- Agents that ask for permission, a sign-in or an answer wait for you. Only real permission prompts can be answered from your phone; questions and sign-ins must be answered at your computer.

## Need help?

Read the [documentation](https://www.pavii.tech/products/dev-tools/docs/), or visit [pavii.tech](https://pavii.tech) and [buckleson.com](https://buckleson.com).

## License

HyperOx is released under the [Apache License 2.0](LICENSE). See [NOTICE](NOTICE) for the components it includes and their licenses.

<p align="center">Made by <a href="https://buckleson.com">Buckleson</a> · <a href="https://pavii.tech">Pavii</a></p>
