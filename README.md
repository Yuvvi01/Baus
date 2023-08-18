# BAUS - Elite Subdomain Brute-Forcing Arsenal
Welcome to BAUS - the powerful subdomain brute-forcing tool built with Python. BAUS, also known as **Haruma**, is your ultimate companion for meticulously exploring target domains by systematically testing a wide range of subdomain combinations curated from a wordlist. With its adaptable configuration options, including support for different HTTP methods and parallel threading, Haruma empowers cybersecurity experts and ethical hackers to swiftly and securely identify potential subdomains, bolstering web security and refining domain reconnaissance strategies.

## Features

- Python-based subdomain brute-forcing tool
- Exhaustive subdomain permutation testing from a wordlist
- Adaptable HTTP methods for customization
- Parallel threading for optimized performance

## Deployment

To get started with BAUS, follow these deployment steps:

1. Installation:

   ```bash
   sudo apt install python3
   git clone https://github.com/Yuvvi01/Baus
   cd baus
   pip install -r requirements.txt

   
2. Activation

Once BAUS is deployed, you can activate it using the following command:

     ```bash 
    python3 pinaka.py -u <url> -w <wordlist> -m HEAD -t 100

