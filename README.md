# Terraform-snapshot-script
shell script for backup &amp; Restore Terraform Enterprise


**HOW TO USE IT :**
- Clone this Repo
- cd terraform-snapshot-script
- Edit Script

  ```shell
  vim tfe-snapshot-install
  ```
- search and change this line with your domain for Terraform backup & Restore API : 
  
  ```shell
  # For Backup
  https://Your-Terraform-Domain/_backup/api/v1/backup
  ```

  ```shell
  # For Restore
  https://Your-Terraform-Domain/_backup/api/v1/restore
  ```
- Add Execute permission for file :
  ```shell
  sudo chmod +x tfe-snapshot-install
  ```
- Install script
  ```shell
  ./tfe-snapshot-install
  ```
  
<br/>

**Commands** :
```
- Restore : tfe-snapshot -r
- Backup  : tfe-snapshot -b
```
