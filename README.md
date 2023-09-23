

---
## Functions

### Admin
- Create Admin account using following command
```
py manage.py createsuperuser
```
- After Login, can see Unit of blood of each blood group available, Number Of Blood bank, Number of blood request, Number of approved request, Total Unit of blood on Dashboard.
- Can View, Update, Delete Blood bank.
- Can View, Update, Delete Patient.
- Can View Donation Request made by Blood bank and can approve or reject that request based on disease of donor.
- If Donation Request approved by admin then that unit of blood added to blood stock of that blood group.
- If Donation Request rejected by admin then 0 unit of blood added to stock.
- Can View Blood Request made by Blood bank / patient and can approve or reject that request.
- If Blood Request approved by admin then that unit of blood reduced from blood stock of that blood group.
- If Blood Request rejected by admin then 0 unit of blood reduced from stock.
- Can see history of blood request.
- Can Update Unit Of Particular Blood Group.


### Blood banks
- Blood banks can create account by providing basic details.
- After Login, Blod bank can donate blood, After approval from admin only, blood will be added to blood stock.
- Blood bank can see their donation history with status (Pending, Approved, Rejected).
- Blood bank can also request for blood from blood stock.
- Blood bank can see their blood request history with status.
- Blood bank can see number of blood request Made, Approved, Pending, Rejected by Admin on their dashboard.
> **_NOTE:_**  Blood bank can donate blood and can also request for blood.





### Patient
- Create account (No Approval Required By Admin, Can Login After Signup)
- After Login, Can see number of blood request Made, Approved, Pending, Rejected by Admin on their dashboard.
- Patient can request for blood of specific blood group and unit from blood stock.
- Patient can see their blood request history with status (Pending, Approved, Rejected).

---

## HOW TO RUN THIS PROJECT
- Install Python(3.7.6) (Dont Forget to Tick Add to Path while installing Python)
- Download This Project Zip Folder and Extract it
- Move to project folder in Terminal. Then run following Commands :

```
python -m pip install -r requirements. txt
``` 

```
py manage.py makemigrations
py manage.py migrate
py manage.py runserver

```
- Now enter following URL in Your Browser Installed On Your Pc
```

```

