What worked in this project:
1. Configuring the Ansible development environment.
2. Installing all required Python packages and Ansible dependencies.
3. Managed to establish a secure VPN connection to the sandbox environment.
4. Also verified SSH connectivity to the managed network device.
5. Managed to execute Ansible playbooks to automate network configuration.
6. I also used Jinja2 templates and RESTCONF to deploy configurations dynamically.
7. I successfully managed to create a local Git repository and pushed the project to GitHub after resolving authentication issues.
What failed in this project:
1. I confused between using VPN and SSH credentials so I took very long connecting to the sandbox environment.
2. The SSH connection for some unknown reason terminated hence I was unable to re-establish connection hence some Ansible commands produced wrong outputs.
Lessons learned:
1. It's important to always verify VPN and SSH connectivity before running automation tasks.
2. Also important to ensure all required dependencies are installed before starting an automation project.
3. Test network connectivity and device accessibility is very key before troubleshooting playbook errors.
4. Systematic troubleshooting and careful verification of each configuration step tends to help resolve issues efficiently and improve the reliability of network automation deployments.
