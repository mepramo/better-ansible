# better-ansible
fix for bad ansible


##To execute as Root
 ansible-playbook main.yml -e "GUID=$GUID"  
 Setup the GUID before running.

##To execute as Normal User
  Copy the ssh keys to the specific user. rg: ec2_user 
