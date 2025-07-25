# CLI Assistant
### CLI Assistant by GoIt-group
CLI Assistant is a command-line interface (CLI) application for managing a phonebook and notes, developed by the CoIt-group-02 team. The application allows users to add, delete, and edit contacts and their phone numbers, add birthdays, and perform other contact- and note-related operations.

To install the application, [follow this link](https://github.com/RomanHarbazh/Final_project_Core.git) and download the repository:
* Unpack the application archive
* Open your terminal and navigate to the folder containing the app:
cd path/to/your/folder

Replace `path/to/your/folder` with the actual path to your unpacked application folder.
* Run `pip install -e clipack` to install the package
* Run `pip install -r requairements.txt` to install all dependencies needed for the app
to function properly

Using the application is very straightforward:
* Make sure the app was installed correctly:
  * Run `pip list` in the terminal
  * Look for `clipack 0.0.1` - if you see this line, everything is working fine! If not, repeat the steps above or contact our [support](qwerty@qwerty.com). [Сапорт](qwerty@qwerty.com) will guide you and help get it working.
* Use the `clipack` command to launch the application in your terminal. 

List of available commands:

Command | Description
:----| :-------------------------------:|
hello | Show all available commands
exit, close or good bye| Exit the program and save all changes
add_contact name birthday | Add a contact to the phonebook
add_phone name phone | Add a phone number to a contact
remove_phone name phone | Remove a phone number from a contact
edit_phone name old_number new_number | Edit a contact’s phone number
find_phone name number | Find a phone number
add_birthday name birthday | Add a birthday to a contact
days name | Check how many days are left until a contact’s birthday
find_user name | Find a specific user in the phonebook
add_secondname name | Add a surname to a contact
edit_secondname name | Edit a contact’s surname
delete_user name | Delete a contact from the phonebook
find_info text | Search users by part of their phone number or name
add_address name address | Add an address to a contact
remove_address name address | Remove a contact’s address
edit_address name address | Edit a contact’s address
add_email name email | Add an email to a contact
remove_email name email | Remove a contact’s email
edit_email name old_email new_email | Edit a contact’s email
birthday_in number | Show users who have a birthday in a given number of days
file_sort path | Sort a folder (enter the path to the folder)
add_note | Add a note
add_note_tags | Add tags to a note
edit_note | Edit a note
delete_note_by_index | Delete a note by index
delete_note_by_title | Delete a note by title
search_note_by_tag | Search for notes by tag
sort_notes_by_tag' | Sort notes by tag
notes_show_all | Show all notes
search_note_by | General note search 


## Notes:
* Before using the application, ensure all dependencies are installed and review the user documentation.

## License:
* This project is distributed without a license. Use it freely and stay healthy!


## Want to tell us how awesome you are or how you can help? [Click here](qwerty@qwerty.com)




