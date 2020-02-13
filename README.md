When using Linkedin API for the first time in a production server, you may get Challenge Exceptions. That's because you never logged in with the given account in that server before. The only way to deal with this problem is logging in manually before calling API. However, in a non-UI and non-browsers environment, you'll need a script to do that.


```shell
python3 -m pip install requirements.txt
python3 linkedin.py <your_email> <your_password>

# Go to your inbox to get the PIN code and enter it if asked
```

