
2021-06-14

* Enhanced `ansible.cfg` and `hosts` to work on Red Hat AA environment
** Enhanced `hosts` to use short names and `ansible_ssh_host`
** Enhanced `hosts` to use GUID and `lookup` filter
* Simplified logic in first (app server) smoketest e.g. `hosts: app1`
* Changed unnecessary `become` privilege escalation in smoketest plays
* Moved the `flask` users password to a var instead of hard coded
