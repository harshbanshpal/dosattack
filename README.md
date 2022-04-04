# dosattack
DoS tool for HTTP requests

# Examples
python harshban.py -g 'https://target.com'

# Usage
usage: harshban.py [-h] [-g G] [-p P] [-d D] [-ah AH] [-t T]

optional arguments:

-h, --help show this help message and exit

-g Specify GET request. Usage: -g '< url >'

-p Specify POST request. Usage: -p '< url >'

-d Specify data payload for POST request

-ah Specify addtional header

-t Specify number of threads to be used
