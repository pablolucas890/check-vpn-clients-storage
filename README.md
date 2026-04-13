# check-vpn-clients-storage

Check your SBCs client storage and notify yourself via slack

## Usage

- Edit credentials with:
  `cp .env.example .env`
- Run:
  `./script`

## Run periodically

- Edit crontab with:
  ```
  * * * * * mkdir -p /tmp/logs/
  0 14 * * * /path/to/check-vpn-clients-storage/script >> /tmp/logs/check-vpn-clients-storage.log
  ```
