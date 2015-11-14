# EDURange - Quick Setup

This page will offer a brief tutorial for a new instructor to get scenarios up and running. 
If you're looking for more advanced documentation on how to take advantage of all the features
of edurange, you can find the instructor manuel at [link]. If you run into trouble with any of the
content covered in this guide, feel free to reach out to [person].

If you are new to edurange, please follow all the steps carefully. The order of steps is important!
 
## Instructor Setup

1. Login to cloud.edurange.org with instructor credentials
2. Give students registration code and have students sign up on cloud.edurange.org
3. Create a student group
4. Add all students to student group
5. Create Scenario
6. Add student group to scenario
7. Boot scenario


### I. Login to cloud.edurange.org with instructor credentials

The credentials to your instructor account should have been emailed to the email you provided.
If you do not yet have an account, please contact [person], and they will email you with
account credentials. Log in to cloud.edurange.org.

### II. Give students registration code and have students sign up on cloud.edurange.org

In order for students to sign up at cloud.edurange.org, they need a registration code.
Once you are logged in as instructor, you can find your the code under the heading,
"Registration Code:" (It is located below AWS Settings and above User Information, it
should be an alphanumeric string like '23a6e9k2a5').

Give this code to your students and have them sign up at cloud.edurange.org. Students will
need to provide the registration code and a name, email, and password.

### III. Create a student group

On your edurange home page (https://cloud.edurange.org/instructor), scroll down to find
the blue button called "Create Student Groups". Once your group is created, you should see
the new empty group under Student Groups, above the default group 'All'.

### IV. Add all students to student group

Once students have registered with the Registration Code you provided them, they should appear
under the 'All' group. To add them to the new student group you have created, click on the blue
'add to student group' located to the right of the student's name and email. Enter the name of 
your newly created student group to add them to the group.

### V. Create Scenario

Select the 'Scenario' tab at the top of the page. Select the white button 'Load New Scenario'.

### VI. Add student group to scenario

Now that the scenario is created, scroll down to the section labeled 'Groups:'. You should see
two sections, 'Instructor' and 'Student'. Click the drop down menu next to student and select
'Add Student Group'. Input the name of the student group that contains your students. It is
important that you add your student group *before* you boot your scenario. If you have already
booted the scenario, unboot it, add the student group, and the boot it again.

### VII. Boot scenario

At the top of the scenario page, click the 'Boot' button on the left. The full booting process
can take anywhere from five minutes on smaller scenarios, to fifteen or twenty on the larger 
scenarios (like recon). Once the scenario is booted and fully initialized, your students should
be able to use their credentials (which they can see once logged into cloud.edurange.edu), to
ssh to the NAT instance.

