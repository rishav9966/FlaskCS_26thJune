# FlaskCS_26thJune
This is a Case Study using Flask Framework, assigned by TCS on 26th June 2020 .

# LOGIN Details
# Ids = [receptionist,diagnostics,pharmacist]
# Password = TCSCS26thJune#    (common for all)

# IMPORTANT POINTS HERE
(Please check this once before starting everyday)
1. Update your hospitals.sql DB with the new file with the command
`mysql hospital < hospital.sql`

#### 2. Change branch to updatesBy(your_name) before committing and PR.

### Steps to start with the project:
1. Install Github Desktop
2. Clone this repository in your Github Folder.(Usually in Documents folder)
3. Open cmd/Terminal. cd to {your_path}/Documents/Github
4. Run command
    ```pip install virtualenv```
5. After successful installation, run the following command
    `python3 -m venv env`
6. Activate env using the command
    `env\Scripts\activate`
7. Installing requirements:
    `pip3 install mysqlclient`.
    `pip3 install flask-mysqldb`.
    `pip3 install -r requirements.txt`.
8. Setting up the database
    `mysql.server start`.
    `mysql hospital < hospital.sql`
    
### Database Tables Schema
![DB_Image](https://github.com/TCSCaseStudy/FlaskCS_26thJune/blob/master/DB%20Logical%20Schema.png)

