Android Seed
==========

This Android Seed provides a MVC (Model-View-Controller) structured project hierarchy to be used in the Android Projects.
For more info on MVC https://en.wikipedia.org/wiki/Model–view–controller.
This seed provides a base for your Android project to start from.

## Components

**Controller** - All the interactions with the users will be covered in the Controllers section. This section will cover all business logic that will used to manipulate its associated view to change the view's presentation.

**Model** - The database related structures will be classified under this section. A model stores data that is retrieved to the controller and displayed in the view. Whenever there is a change to the data it is updated by the controller.

**Services** - This section contains the Java classes for Server interaction and for accessing the models being used in a project (inserting, fetching, deleting and updating). Any access to the database should follow the path “Controller -> Services -> Models. One should never access the Models directly from the Controllers.

**Utilities** - All the files needed for some calculation work inside the app, ServerConfig file, etc will be listed under this section.

**Utilities.AuthLib** - Any external authentication files that are used in the app will be listed here.

**Utilities.Network** - This section contains Java class that one needs to set up a network call to Server. This class have common functions that need to be called for making a Server call.

**Utilities.Globals** - This section will cover fonts, device language, url, keys etc.

**Resources** - This section will covered views, drawables styles etc. The output of this section is represented to user. This mainly contains layout, images, color, string and style files.

__________________________________________________________________________
####NOTE : *Please update this document with every seed updation.*


Copyright 2009-2015 OodlesTechnologies. All rights reserved.