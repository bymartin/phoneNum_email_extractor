# phoneNum_email_extractor

Project Phone Number and Email Address Extractor

Done with macOS 11.5 and Python 3.9.2

From the book Automate the Boring Stuff with Python, 2nd edition
- Chapter 7
- [Webpage](https://nostarch.com/automatestuff2)
- [regex tutorial](https://www.regular-expressions.info)
- [pythex](https://pythex.org) - to test your regex
- [RE docs](https://docs.python.org/3/library/re.html)

## High-level
1. Get text off the clipboard.
2. Find all the emails and phone numbers in the text.
3. Paste the results back to the clipboard.

Install module pyperclip
> pip3 install --user pyperclip

For testing, go to [Test Data](https://nostarch.com/contactus/)
ctrl-A to select all text and ctrl-C to copy to clipboard
Then run program