# devops-project
1. Setup AWS account
   Sign in to aws console
   configure aws in your work station using

   sudo pip install awscli
   sudo aws configure
   Acces ID : Provide security crediantial of your aws console


2.  Install Ansible in your work station

    sudo apt-get install software-properties-common
    sudo apt-add-repository ppa:ansible/ansible

    sudo apt-get install python-pip
    sudo pip install ansible
    sudo apt-get update

3. Install git in your station

   sudo apt-get install git


4.  Clone and run the palybook

    git clone https://github.com/chegurishiva/devops-project.git

    Run Ansible playbook in your work station using

    /usr/bin/ ansible-playbook task.yml

5. EC2 instance will be created in your aws instance

   ping the ip address to any of your browser and refresh twice

6. Apache2 will be installed and open ssl will be created and it redirects http to https


7. To devolop and automate validation of your server congiguration
   
   sudo apt-get install jenkins

   integrate jenkins with git

8. Create a job 

   to test code integrate if sucess launch ec2 instance else notify user with error 


