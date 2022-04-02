# ouiQuery

<h1 align="center"> With ouiQuery, you can easily query for manufacturer strings without reaching out to the internet or external file. </br> You can query a single OUI/MAC address or pass a file of OUIs/MAC addresses to the script.</h1>
</br>

# **Some of the key features are:**

- return manufacturer string for OUI/MAC query
- format agnostic
- ingest a file of OUIs/MAC addresses, returns a file of OUIs/MAC addresses with manufacturer strings for each

# Requirements

- there are no requirements outside of the standard python library.

# Install

To install, clone this repo via the following command line code:

```bash
$git clone git@github.com:theweefies/ouiquery.git
```

Github now requires the use of ssh keys. For information on how to set up ssh keys, [click here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

# **How to run:**
  
  ```bash
  $./ouiQuery.py ff:fe:fc

  OR 

  $./ouiQuery.py file_of_OUIs_or_MACs.txt
  ```
  
  Note: you may need to run this script with sudo. It was made in windows, so you may need to run it through dos2unix to reformat the file. MAC address/OUI octets can be separated with '-' or ':', and either lowercase or uppercase for the alphanumeric characters.
