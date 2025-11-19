                          +-------------------------+
                          |  Remote Worker Laptop   |
                          |-------------------------|
                          | Ubuntu VM               |
                          | Wazuh Agent             |
                          | ClamAV                  |
                          | Google Authenticator    |
                          +------------+------------+
                                       |
                                       | Encrypted VPN Tunnel
                                       |
                          +------------v------------+
                          |      VPN Gateway       |
                          +------------+------------+
                                       |
                                       |
                          +------------v------------+
                          |     Corporate Network   |
                          |-------------------------|
                          |  File Server            |
                          |  App Server             |
                          |  Authentication Server  |
                          +------------+------------+
                                       |
                                       |
                          +------------v------------+
                          |     Wazuh Server       |
                          |   (SIEM Monitoring)    |
                          +-------------------------+
