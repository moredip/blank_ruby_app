# A blank ruby app

Ready for you to start working on!

# Copying repo into a new project
From the blank_ruby_app dir:

   	NEW_APP_LOCATION=/new/project/location
	mkdir $NEW_APP_LOCATION
	git archive master | tar -x -C $NEW_APP_LOCATION
	cd $NEW_APP_LOCATION
	git init
	git add .
	git commit -m 'initial commit, based on blank_ruby_app template'

