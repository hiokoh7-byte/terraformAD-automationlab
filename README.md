# Terraform Active-Directory Automation Lab Steps
# WATCH ME BUILD THIS LAB!: (https://www.loom.com/share/6dbf1ffb253a4764a3d2bb3af9d15ed5)
1. **Preparation (Pre-requisite):** Ensure your directory is scaffolded with the four `.tf` files already populated with code and focused on the folder your "main.tf" is.
2. <img width="1560" height="1360" alt="fourscaffolded" src="https://github.com/user-attachments/assets/6d9916e5-cdb6-4c07-b44e-5b6e12ea8ad3" />

3. **Initialization:** In VS Code, run `terraform init` to prepare the Azure provider.
4. <img width="3830" height="1975" alt="terraforminit" src="https://github.com/user-attachments/assets/356acfe1-7427-4ae2-ae1e-55df98442386" />

5. **Verification:** Execute `terraform plan` to confirm the resources will build correctly in Microsoft Azure.
6. <img width="3827" height="1972" alt="tfplanafter" src="https://github.com/user-attachments/assets/f0e61e0a-2380-4b4c-a0f7-6b108ec56e6d" />

7. **Deployment:** Run `terraform apply` to begin the build process.
   <img width="3812" height="1920" alt="Screenshot 2026-04-20 204522" src="https://github.com/user-attachments/assets/d3516456-9f10-4b7d-9178-fe9603f1cf51" />

8. **The "Wait State":** Allow **3 to 8 minutes** for the VM to install AD DS and reboot automatically.
9. **Access:** Connect via **RDP** using my admin credentials.
10. <img width="3820" height="1927" alt="RDPscreenshot" src="https://github.com/user-attachments/assets/b2de24ba-7890-4309-a15f-44c9f93a7687" />

11. **Final Validation:** Open **PowerShell as Administrator** and run your verification script. If your configuration is correct, the output for domain info, controllers, and DNS should all come back green.
12. From there, I closed out of **RDP** and went to VS Code Editor to run 'terraform destroy to tear everything down in Azure!
13. <img width="3820" height="1930" alt="tfdestroy" src="https://github.com/user-attachments/assets/3e151734-584e-499c-b682-5cde379c29fe" />
