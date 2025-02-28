# Check Validate E-mail Address (Python)

**Description:**

This is a simple Python script to validate an email address based on basic formatting rules. It does not use regular expressions (re) and follows a step-by-step approach

**How It Works:**

The script checks an email against these conditions:

✔️ Must be at least 6 characters long

✔️ First character must be a letter

✔️ Must contain exactly one @ symbol

✔️ Must have a valid domain (.com, .in, etc.)

✔️ Cannot contain spaces or uppercase letters

## Example Inputs & Outputs:  

| Input               | Output                            |
|---------------------|---------------------------------|
| test@domain.com    | ✅ Valid email                  |
| 9test@domain.com   | ❌ Email must start with a letter |
| test@@domain.com   | ❌ Invalid '@' usage             |
| test@domaincom     | ❌ Invalid domain format         |
| test@domain.com@   | ❌ Invalid '@' usage             |
| test@domain. com   | ❌ Invalid email format          |

Outputs:


![image](https://github.com/user-attachments/assets/27524ce5-5731-44d2-a1fe-c86c020744f1)


![image](https://github.com/user-attachments/assets/ee8ee2bb-37d0-4d1b-9802-8c0b3a074229)


