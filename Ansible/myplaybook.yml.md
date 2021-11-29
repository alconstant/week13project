---
  - name: Web Configuration DVWA
    hosts: webservers
    become: true
    tasks: 


    - name: Install docker.io
      apt:
        name: docker.io
        state: present
        force_apt_get: yes
        update_cache: yes

    - name: Install Python3
      apt:
        name: python3-pip
        state: present
        force_apt_get: yes
        update_cache: yes

    - name: Install python docker
      pip:
        name: docker
        state: present
   
    - name: Download and create web container
      docker_container:
        name: dvwa
        image: cyberxsecurity/dvwa
        state: started
        restart_policy: always
        published_ports: 80:80

    - name: Enable docker service
      systemd:
        name: docker
        enabled: yes