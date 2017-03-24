# ansible-role-docker

## Security
- [ ] 1.1 partition /var/lib/docker
- [ ] 2.6 & 3.{7-14} - TLS
- [ ] 2.8  - Enable user namespace support
- [ ] 2.11 - Use authorization plugin - https://github.com/twistlock/authz
- [ ] 2.12 - Configure centralized and remote logging

### Testing
```bash
git clone https://github.com/docker/docker-bench-security.git
cd docker-bench-security
sh docker-bench-security.sh
```