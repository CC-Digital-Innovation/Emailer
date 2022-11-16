# Emailer

## Summary
Python script that is able to send an email with attachments given a sender 
email, recipient email, and SMTP connection information. Allows the user to 
customize the email's body and subject.

_Note: If you have any questions or comments you can always use GitHub
discussions, or email me at farinaanthony96@gmail.com._

#### Why
Many scripts generate an output file. These output files usually are in the 
form of reports and need to go to a reporting email address or can be sent 
to someone's inbox to notify them.

## Requirements
- Python >= 3.9.2
- configparser >= 5.0.2

## Usage
- Enter the SMTP server information, the sender / recipient information, 
  and the email contents into the config.ini file.

- Simply run the script using Python:
  `python Emailer.py`

## Compatibility
Should be able to run on any machine with a Python interpreter. This script
was only tested on a Windows machine running Python 3.9.2.

## Disclaimer
The code provided in this project is an open source example and should not
be treated as an officially supported product. Use at your own risk. If you
encounter any problems, please log an
[issue](https://github.com/CC-Digital-Innovation/NetCloud-Failover-Reporter/issues).

## Contributing
1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request ツ

## History
- version 1.1.4 - 2022/11/16
    - Need to convert port to int for SMTP method


- version 1.1.3 - 2022/11/16
    - Removed license from README.md (already a LICENSE file)


- version 1.1.2 - 2021/06/08
    - Added support for multiple config files
    - Updated README.md


- version 1.1.1 - 2021/05/17
    - Made relative path for config.ini
    - Adjusted README.md
  

- version 1.1.0 - 2021/04/12
    - Added CC and BCC support
  

- version 1.0.0 - 2021/03/17
    - Initial release

## Credits
Anthony Farina <<farinaanthony96@gmail.com>>
