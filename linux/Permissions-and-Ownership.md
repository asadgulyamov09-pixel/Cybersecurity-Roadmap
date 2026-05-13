---

# Least Privilege Principle

The principle of least privilege means that users should only receive the minimum level of access necessary to perform their tasks.

This helps reduce:
- unauthorized access;
- accidental damage;
- privilege abuse;
- insider threats.

---

# Access Control

Access control determines:

who can access what

In Linux, access control is implemented through:

permissions;
ownership;
users;
groups.

Users and Groups
whoami
whoami

Displays the current user.

groups
groups

Displays the groups assigned to the current user.

Risky Permissions
chmod 777 risky.txt

This permission is dangerous because everyone can:

read;
write;
execute the file.

Potential risks include:

unauthorized modification;
malware execution;
privilege abuse.
Secure Permissions
chmod 600 secure.txt

This is safer because only the owner can:

read;
write.

This helps protect sensitive data and reduce unauthorized access.
