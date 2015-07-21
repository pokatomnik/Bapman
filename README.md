# Bapman

Bapman is a VERY simple password manager that requires pwgen. It can generate and store passwords in ~/accounts.txt
Record format:
	date_time : account name : password : comment

Copy theese scripts to /usr/bin to make them accessible via terminal.

Notice: make sure that your ~/accounts.txt is accessible to you only (0600 will be fine)

Usage:

newacc <account_name> ["comment"]
	Adds new record to a text database locacted at ~/accounts.txt with account_name and comment.

newacc <account_name>
	Adds new record to a text database locacted at ~/accounts.txt with account_name
	
findacc <some_text>
	Searches for some_text in the database ~/accounts.txt
