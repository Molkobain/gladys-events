Gladys Project Events
=======================

![Alt](http://gladysproject.com/assets/images/presentation/facebook_share_gladys.jpg)

More about the project on our website : [Gladys Project](http://gladysproject.com).

Life Events
-------------

Here are all the Life Events Gladys actually support. Don't hesitate to add yours with a pull request.

Your event need to be in json, formatted like that :
 
```
{ 
		"name": "yourUniqueName", 
		"BeautifulName" : "Event name",  
		"faIcon" : "fa fa-bed", 
		"iconColor": "bg-yellow"
}
```

name: Must be a **unique** name. Look at events.en.json if it does not exist before submitting your name.

BeautifulName: A name that can be displayed on the user interface. Must be in the language of the file ( events.en.json = english )

faIcon: A Font Awesome icon name, you can found the list [here](https://fortawesome.github.io/Font-Awesome/icons/).

iconColor: The color of the notification icon (you can find examples in the events.en.json file) 