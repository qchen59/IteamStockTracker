# Item Stock Tracker
[![Build Status](https://app.travis-ci.com/qchen59/ItemStockTracker.svg?branch=main)](https://app.travis-ci.com/qchen59/ItemStockTracker)
[![Coverage Status](https://coveralls.io/repos/github/qchen59/ItemStockTracker/badge.svg?branch=main)](https://coveralls.io/github/qchen59/ItemStockTracker?branch=main)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/qchen59/ItemStockTracker)
<a href="https://zenodo.org/badge/latestdoi/404936268"><img src="https://zenodo.org/badge/404936268.svg" alt="DOI"></a>
![GitHub issues](https://img.shields.io/github/issues/qchen59/ItemStockTracker)
![GitHub all releases](https://img.shields.io/github/downloads/qchen59/ItemStockTracker/total)

\<Name TBD\> (Item Stock Tracker) is a program designed to alert users when specific items from an online retailer are back in stock.



https://user-images.githubusercontent.com/34405372/135356983-439e7808-8268-41aa-ad82-38615d4a773e.mp4



### Prerequisites
Make sure you have installed and followed all of the following prerequisites on your development machine:

* Python-- [Download & Install Python 3.9](https://www.python.org/downloads/release/python-390/)
* Email-- Fill out the email address(gmail_user) and password(gmail_password) in SendEmail.py as the sender email
* pillow-- [Download & Install Pillow for python with version>=8.3.0](https://pillow.readthedocs.io/en/stable/)
* requests-- [Download & Install Requests for python with version~=2.26.0](https://docs.python-requests.org/en/latest/)
* beautifulsoup4-- [Download & Install Beautifulsoup4 for python with version~=4.10.0](https://pypi.org/project/beautifulsoup4/)
* lxml-- [Download & Install lxml for Python with version~=4.6.3](https://lxml.de)
* setuptools-- [Download & Install setuptools for Python with version~=57.0.0](https://pypi.org/project/setuptools/)


### Usage

To use our program, download this repository and run the `GUI.py` file that can be found in the `code` directory. After running that file, you should see a GUI like the one below:

![image](https://user-images.githubusercontent.com/30803969/134994728-681060a5-626a-4f5b-85b1-0936a7a9a697.png)

By default, the GUI will already contain some data, which is loaded from `data/tracker.txt`. To add your own items, click the plus button in the upper right. You will be prompted to enter a name for the item you are tracking, along with a URL for a specific product page. Currently, `amazon.com` and `bestbuy.com` product pages are supported.
  
![image](https://user-images.githubusercontent.com/30803969/134995508-7de37397-a552-4af9-82aa-94f13aca6830.png)

You can also edit, add, or delete items by right-clicking on a selected item:
  
  ![image](https://user-images.githubusercontent.com/30803969/134995597-1460417a-a0df-42d4-92a9-c0c0802fa67b.png)

When an item is restocked, a popup will appear. Optionally, an email alert will also be sent to a specified address.
  
  ![image](https://user-images.githubusercontent.com/30803969/134995936-a4088c47-229a-43cf-b01d-a9ae6e787b7b.png)
  
Lastly, in the "Settings" tab you can adjust the refresh interval (how often the program will poll the website to check the stock status of your items), and configure your email alert settings.

  ![image](https://user-images.githubusercontent.com/30803969/134995891-10801bc1-8d94-44be-8e01-1f4bd80fb68d.png)



### Questions?
Contact email: jyang31@ncsu.edu, ncsuemailtest@gmail.com
