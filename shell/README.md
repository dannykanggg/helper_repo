## Shell Commands



### Sending Mail
- mail -s 'subject' "recipient email" <<< "body of email"

### Sending Mail with body text from .txt file
- mail -s 'subject' "recipient email" <<< "$(cat textfile.txt)"
