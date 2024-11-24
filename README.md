# LoginRegistrationAppIdentity
 Login & Registration App using Identity Framework

 >> STEP 1
	Add Identity Framework into the project.
	Select Identity Framework features you want into the project.
	Make DBContext Class and model class.
	After Adding Identity there is a folder called "Areas" appears.

>> STEP 2
	Add Register/Login Links in the navbar
	We have to call a "_LoginPartial.cshtml" partial view in our Layout page by using partial tag.
	"_LoginPartial.cshtml" partial view is located in View/Shared folder, and that is added by identity.

>> STEP 3
	Add some properties in application user class.
	Register these properties or configure in DbContext class.

>> STEP 4
	Now add connection string inside appsettings.json
	Add migration
	Update-Database

>> STEP 5
	Now add TextBoxes for FirstName and LastName in register page.