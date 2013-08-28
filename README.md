contact converter app: 2c
=======

Author:         Phillip Krause
Organisation:   Freie Universität Berlin

Description
The program enables *you* to serve an app, which enables your *user* to convert thair contact-files.

Input format: 
- Thunderbird address book export CSV file
- Thunderbird address book export LDIF file
- Thunderbird address book file itself MIME Type: MAB - Format MORK DB

Output format:
- CSV file for an Outlook import

Special interests:
- keep either german or all special characters and umlauts in names 
- use encoding utf-8, which means, 
  1. Detect encoding of a file
  2. encode it to utf8, if the file's format isn't utf8
  3. convert the file to output format and send it back to user
- be the most meintainable as possible, which means
  1. provide column-mapping tables as text-file (xml-files)
  2. provide configuration as xml-files
  2. clear and commented source-code
  3. make use of common python modules and distribute very spezials modules within this projekt



