# Algorithm-for-file-updates-in-Python

## Project description

At a healthcare company, I was responsible for keeping access to sensitive patient data secure. Access was controlled through a file called `allow_list.txt`, which stored the IP addresses of employees permitted to log into a restricted subnetwork. A separate remove list identified employees who should no longer have access.
To streamline this process, I created a Python algorithm that automatically checked the `allow_list` against the `remove_list`. The script removed any IP addresses that appeared in both lists and updated the `allow_list` file with only the approved entries


## Open the file that contains the allow list

To begin, I stored the filename in a variable called `import_file`:
