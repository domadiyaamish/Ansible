

# Ansible
Ansible is an open-source automation tool that allows you to manage and configure computer systems, deploy applications, and orchestrate complex IT tasks. It is designed to simplify the process of automating tasks such as software deployment, configuration management, and infrastructure provisioning.

Ansible operates by connecting to remote systems through SSH or PowerShell, depending on the target system, and uses a simple, human-readable language called YAML (Yet Another Markup Language) to define automation tasks and configurations. These tasks are organized into reusable units called playbooks.

Playbooks in Ansible describe a set of desired states for systems and specify the steps needed to achieve those states. You can use playbooks to define configurations, install software packages, restart services, and perform various administrative tasks across multiple systems in a consistent and efficient manner.

One of the key features of Ansible is its agentless architecture. Unlike some other automation tools, Ansible does not require any software or daemons to be installed on the managed systems. Instead, it uses SSH or PowerShell to establish a connection and executes tasks remotely, making it lightweight and easy to set up.

Ansible is known for its simplicity and ease of use. Its declarative language and module-based approach make it accessible to both developers and system administrators, allowing them to automate routine tasks and manage infrastructure efficiently. Additionally, Ansible has a large and active community that contributes to its ecosystem, providing a wide range of pre-built modules and playbooks for various use cases.

Overall, Ansible simplifies the process of automating IT tasks and enables efficient management and configuration of systems, making it a popular choice for many organizations and individuals involved in system administration and DevOps practices.


![Logo](https://www.itconductor.com/hubfs/Ansible%20Automation%20IT-Conductor.jpg)


##  Topic which are there

```bash
    - ADHOC Command
        Do one task in ONE MACHINE(localhost)
        Do one task in ONE REMOTE MACHINE
        Do one task in MULTIPLE REMOTE MACHINE using Inventory 
        Do one task in MULTIPLE REMOTE MACHINE using group in Inventory 
    
    - using Playbook(program)
        Do Multiple task in ONE MACHINE(localhost)
        Do Multiple task in ONE REMOTE MACHINE
        Do Multiple task in MULTIPLE REMOTE MACHINE using Inventory 
        Do Multiple task in MULTIPLE REMOTE MACHINE using group in Inventory
        Do Multiple task in MULTIPLE REMOTE MACHINE using group of group in Inventory
        Do Multiple task in MULTIPLE REMOTE MACHINE using environment directory Inventory

    - using Role
        Do One Role in ONE MACHINE
        Do Multiple Role in ONE REMOTE MACHINE
        Do Multiple Role in MULTIPLE REMOTE MACHINE using Inventory
        Do Multiple Role in MULTIPLE REMOTE MACHINE using group in Inventory
        Do Multiple Role in MULTIPLE REMOTE MACHINE using group of group in Inventory
        Do Multiple Role in MULTIPLE REMOTE MACHINE using environment directory Inventory
    
    - Environment Variables
       In Ansible, environment variables are used to store and access information that can be used across playbooks, tasks, and roles. They provide a way to pass dynamic           values or configuration settings to Ansible during execution. Here's a brief explanation of Ansible environment variables:

        ANSIBLE_CONFIG: This variable allows you to specify the location of the Ansible configuration file. It can be set to the path of a specific configuration file to    override the default settings.

ANSIBLE_INVENTORY: It defines the location of the inventory file, which contains information about the managed hosts. By setting this variable, you can use a different inventory file than the default one.

ANSIBLE_REMOTE_USER: Specifies the username used for SSH connections to managed hosts. It allows you to override the default user defined in the inventory or playbooks.

ANSIBLE_PRIVATE_KEY_FILE: This variable holds the path to the private key file used for SSH authentication. It can be set if you want to use a specific key file instead of the default SSH key.

ANSIBLE_VAULT_PASSWORD_FILE: If you use Ansible Vault for encrypting sensitive data, this variable allows you to specify the path to a file containing the password for decrypting the vault-encrypted files.

ANSIBLE_CALLBACK_PLUGINS: Specifies the path to custom callback plugins. Callback plugins are used to customize the output and behavior of Ansible during playbook execution.

ANSIBLE_LIBRARY and ANSIBLE_MODULE_UTILS: These variables define the location of custom Ansible modules and module utilities, respectively. You can use them to extend Ansible's functionality by providing your own modules or utilities.

ANSIBLE_RETRY_FILES_ENABLED: When set to "False," this variable disables the creation of retry files, which are used to track failed tasks and allow for automatic retries on subsequent playbook runs.

These are just a few examples of the environment variables used in Ansible.

    - Fact Variables

    - Playbook Coditioning

    - Playbook Iteration

    - Playbook Running ext scripts

    - Playbook - templaters

    - Playbook - Handlers

    - Exception Handling using Block

    - Ansible Roles

    - Ansible Galaxy

    - Ansible with Windows

    - Ansible Tower
    
        
        
        
        
```


