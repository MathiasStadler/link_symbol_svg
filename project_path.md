# The detailed project path  

## Project name => prompt_rust_ibkr_search_put_ratio_credit_spread

## Project target

## Repo for the symbol to mark web links [![alt text][1]](./README.md)

## Project start date

```bash <!-- markdownlint-disable-line code-block-style -->
$ date
Wed May 21 09:17:17 AM CEST 2025
```

## Hardware

### Install How do install lshw  on debian and usw it [![alt text][1]](https://www.tecmint.com/commands-to-collect-system-and-hardware-information-in-linux/)
<!--- THis empty line inside the block is necessary for correct format -->
        ```bash<!-- markdownlint-disable-line code-block-style -->
        sudo apt update
        sudo apt install lshw
        ```
    <!--- THis empty line inside the block is necessary for correct format -->
    ### used
    <!--- THis empty line inside the block is necessary for correct format -->
        ```bash<!-- markdownlint-disable-line code-block-style -->
        sudo lshw -class cpu -class memory
        [sudo] password for trapapa:
        *-cpu
            description: CPU
            product: Intel(R) Core(TM) i5-3470 CPU @ 3.20GHz
            vendor: Intel Corp.
            physical id: 42
            bus info: cpu@0
            version: 6.58.9
            slot: SOCKET 0
            size: 2836MHz
            capacity: 3800MHz
            width: 64 bits
            #truncated
        *-memory
        description: System Memory
        physical id: 41
        slot: System board or motherboard
        size: 16GiB
        #truncated
        >```
    ><!--- THis empty line inside the block is necessary for correct format -->
    &nbsp;
    <!--- THis empty line is necessary for correct format -->

### OS-Version

```bash
cat /etc/os-release 
PRETTY_NAME="Debian GNU/Linux 12 (bookworm)"
NAME="Debian GNU/Linux"
VERSION_ID="12"
VERSION="12 (bookworm)"
VERSION_CODENAME=bookworm
ID=debian
HOME_URL="https://www.debian.org/"
SUPPORT_URL="https://www.debian.org/support"
BUG_REPORT_URL="https://bugs.debian.org/"
```

## OS-Version - uname

```bash <!-- markdownlint-disable-line code-block-style -->
$ uname -a
Linux debian 6.1.0-28-amd64 #1 SMP PREEMPT_DYNAMIC Debian 6.1.119-1 (2024-11-22) x86_64 GNU/Linux
```

## IDE - MS Visual Studio Code

```text
Version: 1.100.2
Commit: 848b80aeb52026648a8ff9f7c45a9b0a80641e2e
Date: 2025-05-14T21:47:40.416Z
Electron: 34.5.1
ElectronBuildId: 11369351
Chromium: 132.0.6834.210
Node.js: 20.19.0
V8: 13.2.152.41-electron.0
OS: Linux x64 6.1.0-34-
```

>[!NOTE]
>Different curl vs wget [![alt text][1]](https://daniel.haxx.se/docs/curl-vs-wget.html)

## Download via wget [![alt text][1]](https://askubuntu.com/questions/207265/how-to-download-a-file-from-a-website-via-terminal)

```bash
mkdir -p img && wget  -P img/ "https://raw.githubusercontent.com/MathiasStadler/link_symbol_svg/360d1327d05280d53de5fa816c522f89a35891ca/img/link_symbol.svg"
```

## Download via cURL [![alt text][1]](https://stackoverflow.com/questions/32330737/ubuntu-using-curl-to-download-an-image) man page [![alt text][1]](https://linux.die.net/man/1/curl)
<!-- markdownlint-disable MD032 -->
>-O --remote-name **UPPER LETTER**
                Write output to a local file named like the remote file we get.  
>--create-dirs
                When used in conjunction with the -o option, curl will create the necessary local directory hierarchy as needed.
- - --output-dir ``<dir>``
              This option specifies the directory in  which  files  should  be
              stored, when -O, --remote-name or -o, --output are used
> 
<!-- markdownlint-enable MD032 -->
```bash
curl --create-dirs --output-dir img -O  "https://raw.githubusercontent.com/MathiasStadler/link_symbol_svg/360d1327d05280d53de5fa816c522f89a35891ca/img/link_symbol.svg"
```

I never plan never far ahead. Carpe diam

<!-- Link sign - Don't Found a better way :-( - You know a better method? - send me a email -->
[1]: ./img/link_symbol.svg
