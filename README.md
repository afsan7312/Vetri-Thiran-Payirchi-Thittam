#project demo video
click here to watch demo video(https://drive.google.com/file/d/1fyHypeV__ozunYAcyzHTPzhD5X4CzGXu/view?usp=drivesdk)
## 👥 Project Team Details

* **Team Leader:** A. Arshina Afsan
* **Team Members:** 
  * Afrose
  * Asma
  * Asmiya
  * Anushka

---

## 📝 Project Summary

This project demonstrates the implementation of a **Script-Controlled Access Control List (ACL)** in ServiceNow to restrict record access based on specific field values.

### Key Implementations:
* **User & Role Creation:** Created a test user (`EEE User`) and generated custom security roles (`bb1`, `bb2`, `bb3`, and `bb4`) to test different levels of access.
* **Custom Table Development:** Built a custom table named **Institution Details** (`u_institution_details`) with specialized fields including Student Roll Number, Student Name, and Branch choices (ECE, EEE, CSE).
* **Advanced Scripted ACLs:**
  * **Read ACL:** Implemented an advanced JavaScript function ensuring that only users with the `bb1` role can view records belonging to the EEE branch, while securing other data.
  * **Create, Write, & Delete ACLs:** Conditional rules configured with `bb2`, `bb3`, and `bb4` roles to safely manage who can insert, modify, or permanently delete student data.

### Verification Results:
* **Authorized Users:** Users with the `bb1` role can exclusively view EEE branch records.
* **Unauthorized Users:** Users without the designated roles are completely restricted from viewing any data.
* **Administrators:** Admin users retain unrestricted access to view, create, edit, and delete all records across all branches.
