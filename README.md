▀▄▀▄▀▄Municipal Services Management System▄▀▄▀▄▀

Main Menu Navigation
Options: 'Report Issues,' 'Local Events and Announcements,' 'Service Request Status,' and 'News.'
Report Issues Form:
Allows users to report municipal issues like potholes, broken streetlights, or water leaks.
Features include a location combobox, category selection, a description box, and an option to attach media files.
Submissions are stored with a unique ID and timestamp.


Local Events and Announcements:
Displays a list of community events and municipal announcements.
Includes advanced search and filter capabilities based on categories (e.g., "Events" or "Announcements") and dates.
Users can search by event name, category, or specific dates.
Utilizes advanced data structures like SortedDictionary, Dictionary, and PriorityQueue for efficient event storage and retrieval.
Features a recommendation system that suggests events based on previous searches.

Request Service Status
Allow users to track the progress of their reported issues. 
Utilized DataGrid for displaying requests.
Columns: Request ID, Description, Category, Status, Last Updated.
Loaded requests using LoadServiceRequests() method.
Included a refresh button to update data.
Textbox used to search for Service Request by their unique ID
It will display on the dataGrid which number the user entered
Combobox used to filter the Status change the status to "In Progress" or "Resolved".
Designed a user interface using WPF controls like DataGrid to display service request details.

