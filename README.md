# Hi, I'm Lingam

I have 3+ years of experience in infrastructure operations and cloud networking, and I'm moving into network automation.

## Projects

**[AVI VS Health Checker (Python)](https://github.com/Lingam-555/AVI-VS-Health-checker)**

A practice project that fetches virtual services (VS) from an AVI-style API, classifies each one as healthy, warning, critical, down or unknown, and prints a summary. It runs against a local fake server, so no real controller is involved.

*What it shows:*
- Retries only when there is no reply, and never retries a rejected login.
- Pagination with a page limit and a same-host check, so the token is never sent to another host.
- Tests with fake sessions, and mutation checks that prove the tests can fail.

**[AVI VS Health Checker (Ansible)](https://github.com/Lingam-555/AVI-VS-Health-checker-using-ansible)**

Logs in to a practice server running on localhost and downloads the list of virtual services. It saves the list as `output/vs_list.json` next to the playbook, keeping the server's key order.

*What it shows:*
- An idempotent playbook: the second run changes nothing.
- A role with a handler, `no_log` for secrets, and a pinned `ansible-core` version.
- A fresh-clone test that found a hard-coded path.


## Skills, with evidence

| Skill | Evidence |
|---|---|
| Python | [client.py](https://github.com/Lingam-555/AVI-VS-Health-checker/blob/master/client.py) |
| REST APIs | [client.py](https://github.com/Lingam-555/AVI-VS-Health-checker/blob/master/client.py): login, sessions, retries, pagination |
| Testing (pytest) | [test_client.py](https://github.com/Lingam-555/AVI-VS-Health-checker/blob/master/test_client.py) |
| Ansible (basics) | [vs-health.yaml](https://github.com/Lingam-555/AVI-VS-Health-checker-using-ansible/blob/master/vs-health.yaml) |
| Git | [commit history](https://github.com/Lingam-555/AVI-VS-Health-checker/commits/master) |

## Currently learning
GitHub Actions, Docker.

## Planning to start
Terraform.
