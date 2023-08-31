<br/>
<div align="center">
  <a href="https://github.com/proxies-cx/.github">
    <img src="https://github.com/proxies-cx/branding/raw/main/Artboard%202.svg" alt="Logo">
  </a>
</div>

## About
We offer customers the assurance of online anonymity and security through the use of concealed or obfuscated IP addresses. This is accomplished by leveraging IPv6 in place of IPv4, enabling us to deliver requests and connections with a distinct IP every time.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

* [![React][React.js]][React-url]
* [![Go][Go.dev]][Go-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Purchase

1. Register an account at [https://proxies.cx](https://proxies.cx/register)
2. Save your account number
3. Top up your balance [here](https://proxies.cx/dashboard/topup)
4. Purchase a proxy [plan](https://proxies.cx/dashboard/proxies)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage
These are HTTP proxies, here is an example usage with Python:
```py
import requests

proxies_cx = {
    "https": "http://username:password@ip:port"
}
response = requests.get("https://ipv6.wtfismyip.com/text", proxies=proxies_cx)
print(response.text)
```

To use the same IP every request try using our sessions!
```py
import requests

session_id = "abc123" # any random string
proxies_cx = {
    "https": f"http://username:password_session-{session_id}@ip:port"
}
response = requests.get("https://ipv6.wtfismyip.com/text", proxies=proxies_cx)
print(response.text)
```

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact
dropout - [@explosives](https://t.me/explosives) - dropout@fbi.ac

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments
* [FraftDev](https://proxies.gg/)
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>

[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Go.dev]: https://img.shields.io/badge/golang-20232A?style=for-the-badge&logo=go&logoColor=white
[Go-url]: https://go.dev
