<div align="center">
   <a href="https://github.com/1hehaq/loxs"><img src="https://github.com/user-attachments/assets/fb85287c-d9c7-4ffe-86af-d79082e49784" hight="300" width="600" align="center"/></a>
</div>


<br>
<br>
<br>

<div align="center">
   
|Loxs|Multi Vulnerability Scanner|for web application|
|----------------|--------------|-------------|
| `L`| `=`| `Local File Inclusion (LFI)`|
| `O`| `=`| `Open Redirection (OR)`|
| `X`| `=`| `Cross Site Scripting (XSS)`|
| `S`| `=`| `Structured Query Language Injection (SQLi)`|

> **Loxs** is an easy-to-use tool that finds web issues like `LFI` - `OR` - `SQLi` - `XSS`. <br><br> *`Made by`* - [`AnonKryptiQuz`](https://github.com/AnonKryptiQuz) x [`Coffinxp`](https://github.com/coffinxp) x [`HexShad0w`](https://github.com/HexShad0w) x [`Naho`](https://github.com/Naho666) x [`1hehaq`](https://github.com/1hehaq)!

</div>

<hr>

<br>
<br>
<br>


| Features                          | About                                                                       |
|-----------------------------------|-----------------------------------------------------------------------------|
| `LFI Scanner`                     | Detect Local File Inclusion vulnerabilities.                                |
| `OR Scanner`                      | Identify Open Redirect vulnerabilities.                                     |
| `SQL Scanner`                     | Detect SQL Injection vulnerabilities.                                       |
| `XSS Scanner`                     | Identify Cross-Site Scripting vulnerabilities.                              |
| `Multi-threaded Scanning`         | Improved performance through multi-threading.                               |
| `Customizable Payloads`           | Adjust payloads to suit specific targets.                                   |
| `Success Criteria`                | Modify success detection criteria for specific use cases.                   |
| `User-friendly CLI`               | Simple and intuitive command-line interface.                                |
| `Save Vulnerable URLs`            | Option to save vulnerable URLs to a file for future reference.              |
| `HTML Report Generation`          | Generates a detailed HTML report of found vulnerabilities.                  |
| `Share HTML Report via Telegram`  | Share HTML vulnerability reports directly through Telegram.                 |

<br>
<hr>
<br>
<br>

| Language                          | Packages                                                                    |
|-----------------------------------|-----------------------------------------------------------------------------|
| ***Python***| `Python 3.x` `webdriver_manager` `selenium` `aiohttp` `beautifulsoup4` `colorama` `rich` `requests` `gitpython` `prompt_toolkit` `pyyaml` `Flask` `html` `python-telegram-bot`|

<br>
<hr>
<br>

## Installation

### Clone the repository

```bash
git clone https://github.com/1hehaq/loxs.git
cd loxs
```

### Install the requirements

```bash
pip3 install -r requirements.txt
```
### Running the Script

To run the script, use the following command:

```bash
python3 loxs.py
```
<!-- to update the tool to the latest version
```bash
just edit the config.yml file with your tool directory
after pressing 5 and exiting from the tool run the tool again it will run with an updated version
``` -->

----

| Input Information         |                                                                                         |
|---------------------------|-----------------------------------------------------------------------------------------|
| Input URL/File            | Provide a single URL or an input file containing multiple URLs for scanning.            |
| Payload File              | Select or provide a custom payload file for the specific type of vulnerability scanning.|
| Success Criteria          | Define patterns or strings indicating a successful exploitation attempt.                |
| Concurrent Threads        | Set the number of threads for multi-threaded scanning.                                  |
| View and Save Results     | Display results in real-time during the scan, and save vulnerable URLs for future use.  |

----

| Customization              |                                                                                          |
|----------------------------|------------------------------------------------------------------------------------------|
| Custom Payloads            | Modify or create payload files for different vulnerability types to target specific apps.|
| Success Criteria           | Adjust the tool's success patterns to more accurately detect successful exploitations.   |
| Concurrent Threads         | Control the number of threads used during the scan for performance optimization.         |


----

## ChromeDriver Installation Instructions

- Download chrome .deb file:

```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
```

- Install it:

```bash
sudo dpkg -i google-chrome-stable_current_amd64.deb
```

- If you encounter any errors during installation, use the following command:

```bash
sudo apt -f install
```

- After the installation enter this:

```bash
sudo dpkg -i google-chrome-stable_current_amd64.deb
```
- All Done

<hr>

> [!WARNING]  
> Loxs is intended for educational and ethical hacking purposes only. It should only be used to test systems you own or have explicit permission to test. Unauthorized use of third-party websites or systems without consent is illegal and unethical.
