===============
ansible-json
===============

An Ansible plugin for outputting logs to json

Right now, it only outputs to stdout, but in the future it will output to a `.json` file.

# Usage

Make a directory called `callback_plugins` next to your playbook and put `json_logs.py` inside of it

```bash
mkdir callback_plugins
cd callback_plugins
wget https://raw.githubusercontent.com/petems/ansible-json/master/callback_plugins/json_logs.py
```