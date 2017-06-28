# ansible-snap

Installs [snap](http://bowtie-bio.sourceforge.net/snap/index.shtml)

[![Build Status](https://travis-ci.org/CyVerse-Ansible/ansible-snap.svg?branch=master)](https://travis-ci.org/CyVerse-Ansible/ansible-snap)

### Role Variables

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

| Variable                | Required | Default | Choices                   | Comments                                   |
|-------------------------|----------|---------|---------------------------|--------------------------------------------|
| MAKER_HOME                | yes      | /home/MAKER   |         | Directory with enough space. Also where other MAKER dependencies are installed |
