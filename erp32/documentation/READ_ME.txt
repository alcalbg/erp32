
CONTENTS:

1. Before you begin
2. Short description
3. Installation
4. Customization
5. Users Manual
6. Frequently Asked Questions (FAQ)


1. Before you begin:

Consult your accountant about this Software and all features before use.

Our Warranties, Liability and Disclaimers

NEITHER INTERACTIVE32 NOR ITS SUPPLIERS OR DISTRIBUTORS MAKE ANY SPECIFIC PROMISES ABOUT THIS SOFTWARE. FOR EXAMPLE, WE DON�T MAKE ANY COMMITMENTS ABOUT DATA AND CONTENT WITHIN THE SOFTWARE, THE SPECIFIC FUNCTION OF THE SERVICES, OR THEIR RELIABILITY, AVAILABILITY, OR ABILITY TO MEET YOUR NEEDS. WE PROVIDE THE SOFTWARE �AS IS�.

INTERACTIVE32 WILL NOT BE RESPONSIBLE FOR LOST PROFITS, REVENUES, OR DATA, LOSS OF GOODWILL OR BUSINESS REPUTATION, FINANCIAL LOSSES OR INDIRECT, SPECIAL, CONSEQUENTIAL, OR EXEMPLARY DAMAGES IN ALL CASES.



2. Short description

ERP32 is a web-based business management software for small and medium businesses. It allows central management of business processes in your company. 
 
For more info please visit www.erp32.com



3. Installation

Follow these steps to install and configure erp32:

- make sure your have minimum PHP version 5.2 + Apache2
- copy all files to your server (via FTP or similar)
- web server (Apache) must have read/write permissions to all files inside erp32 folder
- import blank_database.sql (or demo_database.sql) from database folder into your mysql server (use phpMyAdmin or similar tool)
- update config.php to reflect your database settings
- you can now log in with initial username and password combination: user1/user1
- default administrator username/password is administrator/admin123. Please change this password inside config.php file

4. Customization

Only administrator can create and manage users. Administrtor can also add new security groups and change users permissions.

You can customize banner and home-page image inside erp32/banner/ folder.

Language files are located here: erp32/app/atk/languages/ you can add new languages or update current files. 
If you add new language make sure your configure it inside admin panel.


5. Users Manual

Users manual is located under users_manual folder and it is also accessible through erp32 main menu
