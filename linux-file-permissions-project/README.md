
# Linux File Permissions Audit  

## Project Objective

Serving as a security professional, the goal of this project was to conduct a filesystem audit within the `/home/researcher2/projects` directory to **ensure compliance with organizational authorization policies**. This involved identifying and correcting excessive or inappropriate permissions that posed a security risk.

## Technical Solution To The Problem

Key Linux administration commands were used to remediate the vulnerabilities:

| Security Task | Command Applied | Impact |
| :--- | :--- | :--- |
| **Verification** | `ls -la` | Used to obtain the 10-character string and interpret initial permissions. |
| **Write Restriction** | `chmod o-w project_k.txt` | Removed write permissions for "others." |
| **Secure Hidden File** | `chmod u=r,g=r .project_x.txt` | Assigned strict read-only authorization to Owner and Group. |
| **Secure Directory** | `chmod g-x drafts` | Eliminated the group's ability to access (execute/enter) the directory. |

## Conclusion

The audit resulted in a more secure file system, where permissions were adjusted granularly to strictly adhere to the Principle of Least Privilege. The intervention ensured the confidentiality and integrity of the research data within the file structure.

---
