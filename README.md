# Medusa v1.0
Medusa is a phishing tool script designed to create phishing pages for various online services. It allows users to set up phishing pages for services like Instagram, Facebook, Twitter, and more. The script facilitates hosting these phishing pages using localhost.run for tunnelling, making it easy to capture user credentials.

# Features
1. Create phishing pages for multiple online services.

2. Host phishing pages using localhost.run for easy access.

3. Customizable phishing page creation for a tailored approach.

4. Catch credentials entered into phishing pages for analysis.

5. Add option to choose either to use default port or custom.

6. The generated phishing link will be displayed, along with its QR code for easy access.

# Dependencies
• PHP: Required for hosting the phishing pages locally.

• SSH: Necessary for creating SSH tunnels using localhost.run.

• XTERM: Necessary to generate link and QR code.

• Note: `setup.sh` installs those dependencies for you

# Supported Environment
## • Kali Linux

## • Parrot security os

## • Debian

## • Ubuntu

## • Arch

# Usage

1. Clone the repository: `git clone https://github.com/emkacztoja/medusa.git`
2. Navigate to the script directory: `cd medusa` 
3. Ensure all dependencies are installed and configured (see Dependencies section).
4. Grants execution permissions to medusa_phisher script: `chmod +x  medusa.sh`
5. Grants execution permissions to setup script: `chmod +x setup.sh`
6. The script installs the required dependencies for running the Medusa Phisher script: `sudo ./setup.sh`
7. Run the script: `sudo ./medusa.sh`
8. Follow the on-screen menu to select a phishing target and start the phishing process. NOTE:The link is generated in the xterm terminal with a QR code too.









# Disclaimer
This script is intended for educational purposes only. The misuse of this tool for illegal activities is strictly prohibited. The author assumes no responsibility for any misuse of this script.

# Author
Emkacztoja | Aleksander Kowalczuk @ GitHub

# License
Medusa is licensed under the [GNU General Public License](LICENSE) and the [MedusaPhisher Commercial License](C-LICENSE)- see the LICENSE file for details.

