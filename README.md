## [Meteor](http://www.meteor.com/) support on CloudBees.

# ClickStacks and CloudBees
This should work with standard meteor apps packaged up of the zip of the application directory - please do ask any questions on
https://groups.google.com/forum/#!forum/cloudbees-dev as we flesh it out.

# Usage

This ClickStarts depends on node.js clickstack. Specify the application type when you deploy an app. 

zip -r app.zip *

bees app:deploy -t nodejs -RPLUGIN.SRC.meteor=https://s3.amazonaws.com/clickstacks/cloudbees/meteor-clickstack.zip app.zip 




