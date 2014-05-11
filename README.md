Ansible Playbook for New Relic
=========================
This will install the New Relic system monitor for Ubuntu/Debian via `apt-get`.

More information on the installation can be found here: http://docs.newrelic.com/docs/server/installation-ubuntu-and-debian

### Sample Usage

##### Use with Tower

- Add this playbook to a **projects** directory available to Tower or through **SCM**.
- Create a **Job Template** using this playbook and provide necessary options.
- Create two variables to pass to this playbook.
	- my_hosts: **groupname**
	- my_new_relic_key: **YOUR-LICENSE-GOES-HERE**
- Run the job and login to New Relic to see magic happen!

### Task List

- [ ] Add check for yum or apt package manager

### Feedback

Please contribute any feedback or problems through this repositories issues or  [@themccallister](https://twitter.com/themccallister).
