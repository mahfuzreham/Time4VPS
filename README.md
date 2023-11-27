![Screenshot](https://github.com/mahfuzreham/Time4VPS/assets/78415545/c537c477-f195-4dd4-ab17-3017064b0aaa)


# WHMCS Time4VPS Module  
  
This is Time4VPS provisioning module for WHMCS platform.   
  
## Installation  
  
 A. Upload archive folder contents to your WHMCS installation root directory.
 B. Login to WHMCS admin panel.
 C. Navigate to `Setup -> Products / Services -> Servers`
 D. Click `Add new Server` button
 E. Set following fields:
	- Name: `Time4VPS`
	- Hostname: `billing.time4vps.com`
	- Type: `Time4VPS Reseller Module`
	- Set your Time4VPS username and password accordingly
F. Create DB tables by navigating to `http://<your whmcs url>/modules/servers/time4vps/install.php` as Admin
  
## Product import/update
##
Code: UPDATE `mod_time4vps` SET `external_id` = '22852' WHERE `mod_time4vps`.`service_id` = 11;



Import / Update Time4VPS products by navigating to `http://<your whmcs url>/modules/servers/time4vps/update.php` as Admin. **Run it once, as every other request will reset any changes you made for existing Time4VPS products.**
  
