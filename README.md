# Google-Hacking
Google Hacking/Google Dork

## Summary

MCSI Remote Internship.

I learned in other to finished my Remote Intership

Below is just a template...................

## Requirements

```
pip install -r requirements.txt
```

Make sure to also [set up your aws credentials](https://github.com/boto/boto3#quick-start) in `~/.aws/credentials`.

## Reconnaissance

Things to do with pre-compromise information gathering.

* validate_iam_access_keys.py - Given a TSV file of access key + secret [+ session] combinations, checks access validity and returns identity information of the principal.
```
./validate_iam_access_keys.py -i /tmp/keys.txt -o /tmp/out.json
```
