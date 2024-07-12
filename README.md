# Nolister
This script enumerates subdomains for a given domain using the SecurityTrails API.
Got it. Here's the revised README file for your script without the specific details about the banner, `tqdm`, and author information:

---

# SecurityTrails Subdomain Enumeration Script

This script enumerates subdomains for a given domain using the SecurityTrails API.

## Features

- Uses the SecurityTrails API to fetch subdomains for a specified domain.
- Prints the full URLs for discovered subdomains.

## Prerequisites

- Python 3.x
- `requests` library
- `tqdm` library

You can install the required libraries using pip:

```
pip install requests tqdm
```

## Usage

1. Clone or download the script.
2. Ensure you have the required libraries installed.
3. Replace the `api_key` variable with your own SecurityTrails API key, or you can leave it if you want limited scans.
4. Run the script.

```
python subdomain_enum.py
```

5. Enter the target domain when prompted.

### Example

```
Enter the target domain (e.g., example.com): example.com

Full URLs for subdomains of example.com:
http://www.subdomain1.example.com
http://www.subdomain2.example.com
http://www.subdomain3.example.com
```


## Notes

- Ensure that you have a valid SecurityTrails API key.
- The script currently assumes that subdomains are prefixed with "www." when constructing full URLs. Adjust the URL construction logic as needed for your use case.

---

Feel free to modify this README file as per your requirements.
