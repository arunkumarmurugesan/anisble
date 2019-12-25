# Wazuh-Ansible 

[![Slack](https://img.shields.io/badge/slack-join-blue.svg)](https://wazuh.com/community/join-us-on-slack/)
[![Email](https://img.shields.io/badge/email-join-blue.svg)](https://groups.google.com/forum/#!forum/wazuh)
[![Documentation](https://img.shields.io/badge/docs-view-green.svg)](https://documentation.wazuh.com)
[![Documentation](https://img.shields.io/badge/web-view-green.svg)](https://wazuh.com)

These playbooks install and configure Wazuh agent, manager, AWS Elastic Stack and postfix. Also, it has a integration with aws cloud trail logs and slack notification.  

## Documentation

* [Wazuh Ansible documentation](https://documentation.wazuh.com/current/deploying-with-ansible/index.html)
* [Full documentation](http://documentation.wazuh.com)

## Directory structure

    ├── wazuh-ansible
    │ ├── roles
    │ │ ├── elastic-stack 
    │ │ │ ├── ansible-elasticsearch        
    │ │ │ ├── ansible-logstash
    │ │ │ ├── ansible-kibana
    │ │
    │ │ ├── wazuh                
    │ │ │ ├── ansible-filebeat
    │ │ │ ├── ansible-wazuh-manager
    │ │ │ ├── ansible-wazuh-agent
    │ │
    │ │ ├── ansible-galaxy
    │ │ │ ├── meta
    │
    │ ├── playbooks
    │ │ ├── wazuh-agent.yml
    │ │ ├── wazuh-elastic.yml
    │ │ ├── wazuh-kibana.yml
    │ │ ├── wazuh-logstash.yml
    │ │ ├── wazuh-manager.yml
    │ │ ├── postfix.yml
   
    │
    │ ├── README.md


## Web references

* [Wazuh website](http://wazuh.com)
