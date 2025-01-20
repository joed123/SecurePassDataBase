To run this program:
1. python3 -m venv venv
2. source venv/bin/activate
3. pip install -r requirements.txt 
4. mysql -u root -p
5. (Enter a password)
6. CREATE DATABASE securepassDB;
7. ctrl + d
7. mysql -u root -p securepassDB < database/DDL.sql
8. python3 app.py



Problem Statement:

A small biotech company discovered a security breach that occurred over the weekend.
Following an investigation, it was found that the backup sample chamber was exposed due to a
weak user password within the login portal. Fortunately the consequences of the breach were
minimal, the company decided to place password standards for all employees and company
devices. Requirements such as: the use of a special character, combination of numbers and
letters, & a minimum length were discussed. Based on NordPass, an average individual
typically maintains around 100 passwords. Accounting for 100 employees and the average of
100 passwords, the database would have to handle 100,000+ entries. Recognizing that the
increased complexity demanded by the new standards would be difficult to remember, the
management team decided to develop an internal tool for generating passwords.




Example run:


<img width="880" alt="Screenshot 2025-01-19 at 8 00 03 PM" src="https://github.com/user-attachments/assets/fe3a9cb2-6d30-4ebf-bc7a-90c2cc9346f8" />
<img width="983" alt="Screenshot 2025-01-19 at 8 00 44 PM" src="https://github.com/user-attachments/assets/76e0a693-2d30-47e5-844b-5e9f2528d323" />
<img width="983" alt="Screenshot 2025-01-19 at 8 01 00 PM" src="https://github.com/user-attachments/assets/2431ed6a-c629-4c95-8c87-3cc59899c968" />
<img width="794" alt="Screenshot 2025-01-19 at 8 01 30 PM" src="https://github.com/user-attachments/assets/29dafdf8-9092-4e60-8844-41235c21219a" />
<img width="963" alt="Screenshot 2025-01-19 at 8 01 48 PM" src="https://github.com/user-attachments/assets/5f11e6a3-22be-49af-adce-34da6085d243" />
<img width="963" alt="Screenshot 2025-01-19 at 8 02 00 PM" src="https://github.com/user-attachments/assets/4420dbeb-c574-400f-a042-6d9151267f13" />
<img width="963" alt="Screenshot 2025-01-19 at 8 02 24 PM" src="https://github.com/user-attachments/assets/99c19072-fe62-4c93-b1a9-16a379f8a2a5" />
<img width="963" alt="Screenshot 2025-01-19 at 8 02 43 PM" src="https://github.com/user-attachments/assets/a721bccb-ff3c-4921-b453-51a630f09afb" />
<img width="963" alt="Screenshot 2025-01-19 at 8 02 50 PM" src="https://github.com/user-attachments/assets/d57862d3-7161-41a7-a252-72cf2d8c289d" />






Some of the Database Tables:


<img width="253" alt="Screenshot 2025-01-19 at 8 08 34 PM" src="https://github.com/user-attachments/assets/87a30098-3823-455e-9ff0-fd42b09dd693" />
<img width="529" alt="Screenshot 2025-01-19 at 8 12 32 PM" src="https://github.com/user-attachments/assets/1b67dd90-86f6-462e-a7cd-78267fea3af4" />
<img width="530" alt="Screenshot 2025-01-19 at 8 09 58 PM" src="https://github.com/user-attachments/assets/71660d62-7032-4042-aa59-e8e36fe33184" />
<img width="417" alt="Screenshot 2025-01-19 at 8 13 01 PM" src="https://github.com/user-attachments/assets/0b4bf7e9-07f4-415d-afa7-065fcdf7ba5a" />
<img width="517" alt="Screenshot 2025-01-19 at 8 13 10 PM" src="https://github.com/user-attachments/assets/4c5bed22-844e-45cf-8a70-0bc44cdf79f7" />
<img width="524" alt="Screenshot 2025-01-19 at 8 42 21 PM" src="https://github.com/user-attachments/assets/82589863-109e-4cef-9e7c-52631f34ee25" />
<img width="354" alt="Screenshot 2025-01-19 at 8 41 51 PM" src="https://github.com/user-attachments/assets/8b7f38ea-9760-4947-8c71-e4d39a5db0b6" />






Key and ERD:


<img width="897" alt="Screenshot 2025-01-16 at 2 54 10 AM" src="https://github.com/user-attachments/assets/06f2a361-f502-49aa-ad5b-a70c0bf38573" />
<img width="884" alt="Screenshot 2025-01-16 at 2 54 50 AM" src="https://github.com/user-attachments/assets/37c2b116-bd9a-4005-84f3-bda64bb3f184" />
<img width="884" alt="Screenshot 2025-01-16 at 2 55 11 AM" src="https://github.com/user-attachments/assets/1d5aa04a-64f6-4a0e-86af-5d5c78d763bf" />
<img width="937" alt="Screenshot 2025-01-16 at 2 53 23 AM" src="https://github.com/user-attachments/assets/0f64638b-515b-4f60-b0ec-83d8b6833080" />
