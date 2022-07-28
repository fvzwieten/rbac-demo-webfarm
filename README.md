# Web Farm Demo

This demo uses the controller_configure projects to load this demo into an empty AAP 2.1+ installation. See the instructions on controller_configure on how to do this.

Use "ansible-playbook redhat_cop.controller_configuration.configure_controller.yml --ask-vault-pass" in this projects root dir to apply the config.
It needs a password to unlock the secrets.yml file which you need. To set up your own see the secrets.yml file in the examples folder.
