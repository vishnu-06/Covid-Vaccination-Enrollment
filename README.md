
# Covid Vaccine Enrollment

Our project is built to solve the current logistical problem of Covid vaccination. People can
use our platform to book vaccination slots from hospitals. Our website partners with the
hospitals to display the number of available vaccines in each hospital, so that the people can
book a slot according to their convenience. Our platform also takes into consideration the
vulnerability of senior citizens, people with comorbidities to covid and prioritises their
vaccination above others, by the use of our ML Algorithm.

## Run Locally

Clone the project

```bash
  git clone https://github.com/vishnu-06/Vaccine-Allotment.git
```

Install dependencies

```bash
  pip3 install -r requirements.txt
```

Go to the project directory

```bash
  cd covid
```

Enable virtual environment
```bash
  source ./venv/Scripts/activate
```

Start the server

```bash
  python3 manage.py runserver
```

Change admin details

[Django Tutorial Part 4: Django admin site](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site#creating_a_superuser)

  
## Authors

- [@vishnu-06](https://github.com/vishnu-06)
- [@PratypartyY2K](https://github.com/PratypartyY2K)



  
## Document
[Link to Document](https://github.com/vishnu-06/Vaccine-Allotment/blob/master/Covid%20Vaccination%20Enrollment.pdf)

  
## Tech Stack

**Client:** HTML5, CSS3, JavaScript, Bootstrap v4.0

**Server:** Django

**Database:** MySQLite DB Browser

  
## Screenshots

**Landing Page**

![Landing Page](/landing-page.png)

**Login Page**

![Login Page](/login-page.png)

**Patient Home Page**

![Patient Home Page](/patient-landing-page.png)

**Choose Hospital**

![Choose Hospital](/choose-hospital.png)

**Allotment Status**

![Allotment Status](/allotment-status.png)

**Hospital Landing Page**

![Hospital Landing Page](/hospital-landing-page.png)

**Vaccine Inventory**

![Vaccine Inventory](/update-inventory.png)
