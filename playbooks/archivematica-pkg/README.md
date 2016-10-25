# archivematica-pkg playbook

The provided playbook installs archivematica on a local vagrant VM, from packages

## How to use
1. Install roles used by the playbook
  ```
  $ ansible-galaxy install -f -p roles/ -r requirements.yml
  ```  
2. Create the test VM using vagrant and provision it 
  ```
  $ vagrant up
  ```
3. To ssh to the VM: 
  ```
  $ vagrant ssh
  ```
4. If you want to forward your SSH agent too, run:
  ```
  $ vagrant ssh -- -A
  ```

