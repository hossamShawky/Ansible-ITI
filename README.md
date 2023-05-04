# Ansible-ITI
<b>this repo for: ansible iti tasks</b>
<ul>
<li>Files of labs</li>
<li>Images of running processes</li>
</ul>

## Notes
### - Lab1:
       - if you have a problem with task=> restart-nginx-task
         - exec your machine [example: ubuntu docker container: docker exec -it docker-name bash]  and run following command

 apt-get remove -y systemd && apt-get autoremove -y

### - Lab2:
      - we use ansible-galaxy to create roles dirctory

        ansible-galaxy init [your-working-dir] [your-destination-role-dir]
   	
      - i added ip [20.245.118.23]  in ineventory file  that refers to ubuntu server in azure, so if you want to test remote machine replace it
                      or not you can remove it to avoid errors.	  
