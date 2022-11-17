# Madpractical11_21012012031
Finished
Study: SQlite Database, RecyclerView, Broadcast Receiver, Service, Notification, Custom Alert Dialog Box, Time Picker Dialog, AlarmManager

AIM: Create Note Android Application that can add Note, edit Note, delete Note, and set reminder date & time of note. By using Broadcast Receiver, AlarmManager set reminder of note. By using SQLite, store all notes data.

Create two Activities like MainActivity, NoteViewActivity according to below UI design.

Use RecyclerView Code from Practical-9 to display Note Data.

Use Broadcast Receiver, Time Picker Dialog, service & AlarmManager code from Practical-7

Create Note class with member variables like id, title, subTitle, Description, modifiedTime, reminderTime:Long, isReminderEnable:Boolean & create membor methods like getCurrentDateTime(), getMillis(), setReminder(), isValid(), getReminderText(), saveNote(), getHour(), getMinute(), calculateReminder()

Create DatabaseHelper Class for SQlite with member methods like insertNote(), getNote(id), getAllNotes(), getNotesCount(), updateNote(), deleteNote().

Use Databinding in gradle file to easy way integrate xml into kotlin file

Use Material 3 design for UI

create class NotesData with companion object and it will store column name of table and create table query.

Create NoteViewActivity. It will show while reminder notification is turned up and user click on notification. It will also show when click on Note in recyclerView. After clicking on notification NoteViewActivity should be open with full description of that note.

Note should be deleted by clicking on icon of Delete. Note should not be added if any one field of note is empty.

Some notes have reminder time so add reminder time in alarmManager with note id & it should be receive in broadcast receiver & in broadcast receiver notification should be generated with title & description of note.

If More than one notes have reminder time then notification should be displayed for each note separately.

Create Common Custom Dialog Box for add, edit note.

Create RecyclerView & its adapter to display all notes.

![WhatsApp Image 2022-11-18 at 12 48 05 AM (1)](https://user-images.githubusercontent.com/110801380/202577078-7d056928-a5e9-45db-b0a3-ed95461975cc.jpeg)
![WhatsApp Image 2022-11-18 at 12 48 05 AM](https://user-images.githubusercontent.com/110801380/202577090-d8bdceff-f980-4a64-9a7b-ede292209061.jpeg)
![WhatsApp Image 2022-11-18 at 12 46 38 AM (1)](https://user-images.githubusercontent.com/110801380/202577114-36a08155-e998-4395-981f-27b0791aaf84.jpeg)
![WhatsApp Image 2022-11-18 at 12 46 38 AM](https://user-images.githubusercontent.com/110801380/202577124-7fb3a478-af20-4f37-a68d-95102f642539.jpeg)
![WhatsApp Image 2022-11-18 at 12 46 37 AM (2)](https://user-images.githubusercontent.com/110801380/202577149-53af95d5-5061-43d9-aa04-3be0ffe64f43.jpeg)
