# MCQwebsite
MCQ Website 
-------------------------
I have done this project in laravel.
The version I have used is: Laravel Framework 7.30.4
And updated version of composer is being used.
If your composer is not updated,you can update it using the command: composer update

GuzzleHttp is required to fetch data from external api.After getting composer updated run the command : composer require guzzlehttp/guzzle.

Then run:-  php artisan serve    command in the terminal .

Features:
------------
You can add,update and delete user categories(as there can be two categories of users:Guest and Admin) .You cannot add usercategory with the same name, For ex:You 
cannot add admin twice.Pagination and search option is added.

You can add,update,delete,activate/deactivate user and reset the password of a user.You cannot add user with the same emailid. For ex:You cannot add the same emailid 
twice for the different users.Pagination and search option is added.

After adding usercategories and user, you van login with your emailid and default password i.e. 123456789.

Guest login can only give the MCQ and see their own score
Admin login can see all the usercategories,user and score of all the users and can also give the mcq.

Database used is postgresql 9.2
