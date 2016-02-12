This page will provide you some basic details about the events layout. 
## Page Requirements

### YAML Front Matter
Each /events page must include YAML front-matter (the block at the top of the page surrounded by triple hyphens) which defines metadata for the page. Copy the front-matter in this template for your new page. Below are some explanations of the different front-matter tags.

* layout
  * Denotes which layout from the _layouts folder should be used when rendering the page. Unless using a custom layout, events is the best bet.
* title
  * What is the title of your event?
* description
  * Provide a one to two sentence summary of your event. This is the snippet that will be shared via social media cards.
* datetimestart
  * Start date and time of the event. Date time should be entered in the following format YYYY-MM-DD HH:MM. For example, 2016-02-10 17:00
* datetimeend
  * Date and time the event will end. Date time should be entered in the following format YYYY-MM-DD HH:MM. For example, 2016-02-10 17:00
* location
  * Street address of the event
* contactemail
  * E-mail address for the event point of contact
* tags
  * Tags can be used to group similar events or blog posts. Multiple tags can be listed for an event using a comma separated string or YAML list

 
## Building an Event Page 

* Template~.html is an example page built using the events layout. For folks new to Jekyll, this is a good place to start. Simply copy the file, rename it, and remove the tilde from the end of the file name.
* The name of the file should match the name of the event but substitute hyphens for spaces. For instance, "Earth Day Hackathon 2016" would have a file named "earth-day-hackathon-2016.html"
* more instructions to come...