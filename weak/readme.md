btnshow_Click

This code runs when you click the Show button.

1. string firstname, secondname, fullname;
Creates three string variables:

firstname → stores the first name.

secondname → stores the second name.

fullname → stores the complete name.



2. firstname = txtfirstname.Text;
Gets the text from the txtfirstname TextBox and stores it in firstname.


3. secondname = txtsecondname.Text;
Gets the text from the txtsecondname TextBox and stores it in secondname.


4. fullname = firstname + " " + secondname;
Combines the two names with a space between them.

Example:
Zamzam + " " + Abdulaziz → Zamzam Abdulaziz


5. lbloutput.Text = fullname;
Displays the complete name inside the lbloutput Label.



btnclear_Click

This code runs when you click the Clear button.

txtfirstname.Clear(); → clears the first-name TextBox.

txtsecondname.Clear(); → clears the second-name TextBox.

lbloutput.Text = ""; → clears the output Label.


In short:
Show button → displays the full name.
Clear button → clears all the fields.