# DatingApp
Web app for users to create a dating profile and match with other users.
- Users will be able to register and login to their registered account.
- Users will be able to add a description and photo to their dating profile
- Users will be able to like other users and see who likes them. 
- Users will be able to live message eachother.
- Users will be able to apply filters to search for relevant dating profiles.

Web app built using .NET to drive the backend API and Angular to drive the front end behavior.

# Home Page
![image](https://user-images.githubusercontent.com/16530058/135024608-405dbbc6-619e-4044-b38d-269dd6b2d5ba.png)


Home page functionality:
- User can click 'Register' and provide a username and password to create an account.
- User can login with their username and password in the NavBar form. Credentials are verified against the back-end database that holds the registered accounts.
- Once a user logs in, their login is persisted until they click the 'Logout' button. This means the user can refresh and navigate to other pages without being logged out.

# Registration Form
![image](https://user-images.githubusercontent.com/16530058/137642929-90bd62d6-12fe-4d2d-8ebf-451d3990b638.png)


Registration form functionality:
- User can provide a username and password to create an account
- User will recieve an error toast message if their password is not between 4 - 12 characters (additional validation will be added in the future)
- User will recieve an error toast message if their username matches another users

# Members Page
![image](https://user-images.githubusercontent.com/16530058/137643317-b6914ba2-6e22-44d3-9e86-fb2f42006710.png)


Members Page functionality:
- User can only access the members page if they have registered an account and logged in
- User can view other created profiles in the system
- User will eventually be able to provide filters to search for profiles relevant to their interests (Age, Gender, ect...)
- Pagination will eventually be implemented

# Member Card
![image](https://user-images.githubusercontent.com/16530058/137643348-d852146c-1a05-43e9-b667-24622cb98f20.png)![image](https://user-images.githubusercontent.com/16530058/137643371-d0bab695-737b-41d9-8ec1-0c374ef038e8.png)


Member Card functionality:
- User can view the given members name, city, and main profile picture.
- User can hover over the card to zoom in on the main profile picture
- User can hover over the card to expose the following buttons: Member Detail button, Like button, Message button
- User can click the Member Detail button to navigate to the Member Detail page
- Like button and Message button will eventually be implemented

# Member Detail Page
![image](https://user-images.githubusercontent.com/16530058/137643523-0c3b8174-929c-43d6-bd55-ee704a7ae64e.png)

Member detail page functionality:
- User can view additional information about the member: Description, Looking For, Interests, Age, Location, Additional photos, Messages
- Messages not yet implemented

Member detail page additional photos:
![image](https://user-images.githubusercontent.com/16530058/137643621-d5c0e2ce-fb49-47ba-9afc-dac38b289993.png)
![image](https://user-images.githubusercontent.com/16530058/137643633-b776c02c-ebc4-46b5-a386-dd54536c1659.png)

# Edit Profile Page
![image](https://user-images.githubusercontent.com/16530058/137643703-227c75e3-7e63-4ca7-99d9-7792081b3d9e.png)

Edit profile page functionality:
- User can edit their info and save their changes
- User cannot save changes if they have not made the form dirty (Save changes button is disabled)
- User is notified if they have made the form dirty with a notification above the form

Built with help of: 
- https://www.udemy.com/course/build-an-app-with-aspnet-core-and-angular-from-scratch/
- https://www.udemy.com/course/the-complete-guide-to-angular-2/?src=sac&kw=Angular+-+the+com
- https://www.udemy.com/course/csharp-tutorial-for-beginners/
- https://www.udemy.com/course/csharp-intermediate-classes-interfaces-and-oop/
- https://www.udemy.com/course/csharp-advanced/
- https://www.udemy.com/course/the-complete-sql-bootcamp/
- https://www.google.com/

