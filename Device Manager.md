# Device Manager

How physical computers laptops phones etc. are allowed to access devices like printers and also cloud.

this is using Device Based Conditional Access DBCA



## Three ways to add devices to AZ AD

1. AZURE AZ REGISTERED - Personal device (not company owned) signed in with personal account (Windows, Mac, IOS, Android) 
2. AZURE AZ JOINED - Organization owned device in the cloud (Windows 10, Windows Server 2019 running on azure VM) signed in using a Organization owned AZ AD account
3. HYBRID AZURE AZ JOINED - Owned by organization signed in with ADDS ACTIVE DIRECTORY DOMAIN SERVICES account. Exist in-cloud and on-premises



---

# 1. AZURE AZ REGISTERED

personal device, signed into using personal account

- Mac OS, android, IOS, Windows
- How to register
- Windows - settings
- android/ios - company portal or Microsoft authenticator
- Mac OS - company portal

## Sign in methods

end user local credential, password, PIN, Windows Hello, Biometrics

---

## Mobile Device Management

## Mobile Application Management

---

# Key Use Cases

1. SSO for cloud applications
2. Conditional access when enrolled into intune
3. Conditional access via App Protection Policy
4. Enables Phone Sign in with Microsoft Authenticator App

---

## Windows Hello

Allows windows users to sign in using biometrics such as fingerprint, iris scan, face scan



---

# 2. AZURE AD JOINED

joined only to organization with AZ AD account needed to sign on

- For cloud devices (Windows 10 VM, Windows Server 2019)
- Password, Windows Hello For Business
- MDM using INTUNE
- Also though Microsoft endpoint configuration manager

## Key Use Cases

1. SSO for cloud and on prem resources
2. Conditional acces through MDM
3. Self service password reset from lock screen
4. Enterprise state roaming across devices

---

# 3. Hybrid Joined

Connected to On-Prem AD and AZ AD

Domain Join by IT or Windows Aut

