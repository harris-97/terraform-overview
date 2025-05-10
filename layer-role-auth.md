| Layer      | Role                                | Auth Method                          |
|------------|-------------------------------------|--------------------------------------|
| *GUI*    | Interactive user access             | Username/password, MFA              |
| *CLI*    | Command-line automation             | Access key + secret, OAuth token    |
| *API*    | Programmatic interaction            | Bearer token, service principal     |
| *IaC*    | Automation tool layer (uses CLI/API)| Inherits CLI/API credentials        |
| *Network*| Data path between systems and cloud | No auth itself; enables access      |
