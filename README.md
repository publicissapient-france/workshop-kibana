kibana-workshop
===============

Install boto from pip (python library)
create a file ~/.boto
    [Credentials]
    aws_access_key_id = <your_access_key_here>
    aws_secret_access_key = <your_secret_key_here>

launch command like
    ansible-playbook -i local site.yml --private-key=kibana.pem --extra-vars "group_kibana=europa" &
