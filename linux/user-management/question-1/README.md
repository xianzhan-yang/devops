Problem: User Management Scenario

Your company has just hired a few new employees, and you need to set up accounts for them on the company's Linux server. The following tasks need to be completed:
1. Create New Users

You need to create three new user accounts:

    alice: A developer who needs standard user permissions.
    bob: A system administrator with sudo privileges.
    charlie: A contractor who should have limited permissions.

2. Set Passwords

Assign the following passwords to each user:

    alice: alice2025
    bob: bobadmin123
    charlie: charlie123

3. Create User Groups

    Create a group called devs and add alice to it.
    Create a group called admins and add bob to it.
    Create a group called contractors and add charlie to it.

4. Assign Specific Permissions

    alice: Should only have access to the /home/alice directory, and be able to create, edit, and delete files there.
    bob: Should have full access to the /etc directory, including all subdirectories, but should not be able to access /home/charlie.
    charlie: Should only have read access to /home/alice and no write or execute permissions.

5. Create a Shared Directory

Create a directory /shared that should be accessible by all three users. However, alice and bob should have write permissions, while charlie should only have read permissions.
