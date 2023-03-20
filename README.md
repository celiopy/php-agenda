Agenda is a php framework which allows the user to create events based on a scheduled time.

How it is displayed depends on how it is decided on frontend as most of the elements depends on visual structure.

The calendar.css tells how the calendar will look, as it is generated as "divs". (I use flexbox to make it looks better and be responsive);
The calendar.php shows what the class.Calendar.php generates.
The agenda.php is the file that calls for calendar.php and also displays the events from the current selected day.

I'll use javascript here to show a modal everytime a user clicks on add (+) an event or when clicks on an event, it will also update the list everytime a user changes the day on the calendar.

Everytime a user clicks a day on the calendar the url bar follows this change, allowing any day to entered in the url bar as /year/month/day to print the events. It also follows the active (editing) event, as /year/month/day/event-id. If the event exists it will automatically open the modal for this event, otherwise it shows the list as normal, but no modal is trigged. Everything here is javascript hungry.

This might be updated for other things as well. Nothing fancy here, but might be useful.
