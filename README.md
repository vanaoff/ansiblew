Blew - Portable Ansible Wrapper
===

Blew makes easy to share build & deployment recipes written in [Ansible](https://github.com/ansible/ansible) without 
necessity to have Ansible installed on the host system.

## Requirements
Internet connection and Python 3  

## Install
```bash
curl -o blew https://raw.githubusercontent.com/vanaoff/blew/master/blew && chmod +x blew 
```

## Usage
```bash
❯ blew --blew-help
usage: blew [--log-level LOG_LEVEL] [--blew-help] {reset,config,connection,console,doc,galaxy,inventory,lint,playbook,pull,test,vault} ...

positional arguments:
  {config,connection,console,doc,galaxy,inventory,lint,playbook,pull,test,vault,reset}

optional arguments:
  --log-level LOG_LEVEL
  --blew-help
```

## Links
https://github.com/ownport/portable-ansible
