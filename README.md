# Project2 -Red Team vs. Blue Team scenario
As the Red Team, you will attack a vulnerable VM within your environment, ultimately gaining root access to the machine. As Blue Team, you will use Kibana to review logs taken
- use the logs to extract hard data and visualizations for their report
- interpret your log data to suggest mitigation measures for each exploit that uccessfully performed.


## ELK Server Setup Instructions


- As the you attack a web server today, it will send all of the attack info to an ELK server.


- The following setup commands need to be run, before the attack takes place in order to make sure the server is collecting logs.


# Pre-Conditions to complete before starting the attack

- Double click on the 'HyperV Manager' Icon on the Desktop to open the HyperV Manager.


- Choose the Capstone machine from the list of Virtual Machines and double-click it to get a terminal window.


- Login to the machine using the credentials: vagrant:vagrant


- Switch to the root user with sudo su

# Setup Filebeat

- Run the following commands:

- filebeat modules enable apache
- filebeat setup


The output  as in screen shot
![](https://drive.google.com/file/d/1G4709a1ZsD1bEJkjbgLioZ9VZZ3CqtOy/view?usp=sharing)
