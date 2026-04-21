# Terraform Active-Directory Automation Lab Steps
# WATCH ME BUILD THIS LAB!: (https://www.loom.com/share/6dbf1ffb253a4764a3d2bb3af9d15ed5)
1. **Preparation (Pre-requisite):** Ensure your directory is scaffolded with the four `.tf` files already populated with code and focused on the folder your "main.tf" is.
 <img width="1560" height="1360" alt="fourscaffolded" src="https://github.com/user-attachments/assets/1257738c-c9e7-456b-96e9-d060190e2eea" />
3. **Initialization:** In VS Code, run `terraform init` to prepare the Azure provider.
<img width="3830" height="1975" alt="terraforminit" src="https://github.com/user-attachments/assets/d9010e30-3449-48d4-9f9a-dbece4fddf8a" />

4. **Verification:** Execute `terraform plan` to confirm the resources will build correctly in Microsoft Azure.
<img width="3827" height="1972" alt="tfplanafter" src="https://github.com/user-attachments/assets/66760594-c8dd-47ef-9233-47418d271e5d" />


5. **Deployment:** Run `terraform apply` to begin the build process.
   <img width="3812" height="1920" alt="RunningTFApply" src="https://github.com/user-attachments/assets/0a7a665f-13b8-4b2b-8e42-1c56c85ad254" />

6. **The "Wait State":** Allow **3 to 8 minutes** for the VM to install AD DS and reboot automatically.
7. **Access:** Connect via **RDP** using my admin credentials.
 <img width="3820" height="1927" alt="RDPscreenshot" src="https://github.com/user-attachments/assets/09735e0b-86e8-4d8e-97cf-e5a6927fc7eb" />

8. **Final Validation:** Open **PowerShell as Administrator** and run your verification script. If your configuration is correct, the output for domain info, controllers, and DNS should all come back green.
9. From there, I closed out of **RDP** and went to VS Code Editor to run 'terraform destroy to tear everything down in Azure!
 <img width="3820" height="1930" alt="tfdestroy" src="https://github.com/user-attachments/assets/71215033-6d4b-4cba-8eec-50dad02210a8" />

