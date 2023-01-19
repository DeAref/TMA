# TMA
Telegram group Scraper And Adder

edit line 6-7-8 in both files
```
api_id = 2424389   #Enter Your 7 Digit Telegram API ID.
api_hash = 'c9330a39435d0b1084d2ffc2s5965a7f'   #Enter Yor 32 Character API Hash.
phone = '+989955663322'   #Enter Your Mobilr Number With Country Code.
```

Get api_id from https://my.telegram.org/
------------

## Start
1. select the group whose members you want to extract. Then extract the members' IDs with the `scraper.py` file.

The scraped members are saved in a .csv file

2. edit `Adder.py` line 31 and add csv file path.

3. run `Adder.py`. 
