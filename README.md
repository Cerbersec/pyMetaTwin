# pyMetaTwin

pyMetaTwin is a Python3 implementation of [MetaTwin](https://github.com/threatexpress/metatwin) that allows you to copy metadata and digital signatures from one Windows executable to another using Wine on a non-Windows platform.

## Requirements

- Python 3.x
- Wine
- Resource Hacker
- SigThief

## Installation

To install the necessary dependencies, run the `install.sh` script provided in this repository.

```bash
chmod +x install.sh
./install.sh
```

## Usage

After installing the required dependencies, you can run the script as follows:

```bash
python3 metatwin.py <source_file> <target_file>
<source_file> is the path to the Windows executable file from which you want to copy the metadata and digital signature.
<target_file> is the path to the Windows executable file to which you want to copy the metadata and digital signature.
```

Make sure that both ResourceHacker.exe and SigThief.exe are installed and accessible in your system's PATH or pyMetaTwin's working directory.

## Resources

* [Resource Hacker](https://www.angusj.com/resourcehacker/)
* [SigThief](https://github.com/secretsquirrel/SigThief)