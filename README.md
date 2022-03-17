# test
# Pipeline


steps:

  - command: "git pull origin master"
    label: "git pull origin master"
    
  - wait
  - command: "hostname"
    label: Hostname
