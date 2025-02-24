# Blood Center Project

Hello! You have been hired to develop a blood donor registration system for the Blood Center in your city, using JavaScript and the readline-sync function for data input.
The program should allow the registration of donors and must contain the following information: name, age, weight, blood type, and the date of the last donation.

## Install dependencies:
```js
npm install
```

When accessing the system, the user should be presented with a menu containing the following options:
```markdown
===== BLOOD DONOR REGISTRATION SYSTEM =====
1. Register donor
2. List donors
3. Search donor by blood type
4. Search donor by last donation date
5. Exit
Choose an option:
```

**1. Register donor:** This option allows registering a new donor in the system. The program should request the donor's name, age, weight, blood type, and last donation date. The system should store these details in an object and save the object in an array of donors.

**2. List donors:** This option lists all registered donors in the system, showing their complete information.

Example: 

```markup
--------------------
LIST OF DONORS:
--------------------
NAME             | AGE  | WEIGHT | BLOOD TYPE | LAST DONATION
-----------------------------------------------------------------
John Silva      |  25  |  70    |     AB-     |  01/01/2022  
Maria Santos    |  35  |  65    |     A+      |  03/02/2022  
Jose Almeida    |  45  |  80    |     O+      |  10/01/2022  
Ana Oliveira    |  27  |  58    |     B-      |  22/04/2022  
Carlos Silva    |  30  |  75    |     A-      |  14/03/2022  
-----------------------------------------------------------------
```

**3. Search donor by blood type:** This option allows searching for donors by their blood type. The program should ask for the desired blood type and list all donors with that blood type.

```markup
Enter the desired blood type: A+

------------------------
SEARCH RESULT:
------------------------
NAME             | AGE  | WEIGHT | BLOOD TYPE | LAST DONATION
-----------------------------------------------------------------
Maria Santos    |  35  |  65    |     A+      |  03/02/2022  
Carlos Silva    |  30  |  75    |     A-      |  14/03/2022  
-----------------------------------------------------------------
```

**4. Search donor by last donation date:** This option allows searching for donors who made their last donation before a specific date. The program should request the desired date and list all donors who made their last donation before that date.

Example:
```markup
Enter the desired date (dd/mm/yyyy): 01/03/2024

------------------------
SEARCH RESULT:
------------------------
NAME             | AGE  | WEIGHT | BLOOD TYPE | LAST DONATION
-----------------------------------------------------------------
Calito Teves     |  35  |  65    |     A+      |  01/03/2022  
Carla Maria      |  30  |  75    |     A-      |  01/03/2022  
-----------------------------------------------------------------
```

**5. Exit:** The program should terminate.
