# Basic_Ansible-Deploy with Ec2 Instance
  
  We Can create an Ec2 instance after select SSh_id and copy paste in git bash 
  cat /etc/os-release
  sudo su -l after changes to root user
  sudo apt update #update 
  sudo apt install ansible # ansible install
  ansible  --version
  sudo apt install python-pip  #python install
  sudo apt install python3-pip #python3 install & pip install
  pip --version
  python3 --version
  pip install boto #boto install
  ansible-doc ec2 #ansible documents for ec2 variables inside commands
  vim .vimrc for .vimrc file  & :set nu for #allign the line 
  vim create.yml #create or edit data in yml file
  ansible-playbook --syntax-check create.yml #Syntax for yml file
  ansible-playbook -C create.yml #Demo file
  ansible-playbook  create.yml #deployed yml file in Ansible playbook
  

# Git error: failed to push some refs to  current repo url
rm -rf .git
git init
git remote add origin URL
git remote -v (to see the remote origin)
git add -A(add all files)
git commit -m 'Added my project'
git pull --rebase origin master
git push  origin master
