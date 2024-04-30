#  $${\color{red}Under Construction}$$

# QA-Automation-Project-API-Swagger-Parabank

## Am creat fisierul **request_accountID.py**

```
markdown

import requests

# Test account ID
account_id = "12345"

# Construct the API request URL
url = f"http://parabank.parasoft.com/parabank/services/bank/accounts/123654"

# Send a GET request to the URL
response = requests.get(url)

# Check if the request was successful (status code 200)
if response.status_code == 200:
    # Print the response data (transactions)
    print("Transactions:")
    print(response.json())
else:
    # Print an error message if the request was not successful
    print("Error:", response.status_code, response.text)
```
