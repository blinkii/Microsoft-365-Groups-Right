# Office-365-Teams-Allow
Allow or Block Teams creation into Microsoft Teams

## Step 1: Create a group for users who need to create Microsoft 365 groups
Only one group in your organization can be used to control who is able to create Microsoft 365 Groups. But, you can nest other groups as members of this group.

Admins in the roles listed above do not need to be members of this group: they retain their ability to create groups.

In the admin center, go to the Groups page.

Click on Add a Group.

Choose the group type you want. Remember the name of the group! You'll need it later.

Finish setting up the group, adding people or other groups who you want to be able to create groups as members (not owners).

For detailed instructions, see Create, edit, or delete a security group in the Microsoft 365 admin center.

## Step 2: Run the Script
Run the script and insert the group name create in step 1
Choose False for block creation for all user exept the group
