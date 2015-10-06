# Working with Arrays
Sinatra app to work with arrays

## To get started

1. Open the Terminal/Command line tool of your choice (terminal on mac and cmd on windows)
2. Navigate to where you want these files to reside
2. Clone this repository
3. If you haven't yet, enter **gem install sinatra** and **gem install rerun** at the command line
4. Now run **ruby run.rb** or **rerun 'ruby run.rb'** (recommended)

## Create your own repository
1. On your github account, create your own repository called "Working with Hashes"
2. Clone it to your computer (instructions can be found on your repository home page)
3. Copy the files from the MGTI repo to your repo
4. Add files (git add .) and then commit (git commit -am 'initial files' )

## To start the homework application:

1. Open **run.rb** and **form.erb** files in the **views/** folder
2. If you haven't started the app, see step 4 above.
3. Once the server is running, open your browser to http://localhost:4567
4. If you just launched the app with **ruby run.rb**, you will need to restart with every change.

## Here are the steps to complete:

- [ ] Create an array called states
- [ ] Create a hash called state
  * Hash should have two keys ("id" and "name")
  * The keys should be symbols
- [ ] Add the state hash to the states array
- [ ] Repeat steps 2-3 until you have at least 5 state hashes in the array
- [ ] Make sure that the array of states are sorted alphabetically on the state's name
- [ ] Add the following fields:
  * Full Name (text)
  * Address (textarea)
  * City (text)
  * State (select box)
  * Zip (text)
  * I agree... (checkbox, value of 1)
- [ ] Use the array of states to populate the drop down select box. The value should be the state’s ID and each option should display the state’s name.
- [ ] Use the params hash to check and see if the form has been submitted.

If the form has been submitted:
- [ ] Add a message at the top of the page that states the form has been submitted.
- [ ] Populate the default values of each text and textarea field with the values previously submitted.
- [ ] Default the state select list to the state previously submitted.
- [ ] If the checkbox was previously checked, default it to “checked”. If it wasn’t checked, default it to not being checked.
- [ ] Make sure they HTML that is generated is proper and valid HTML. For instance, form elements should have an associated label.

## Tips

Tips:
- You may want to set the name and value of the submit button to something specific and check the params hash for the submit button’s hash key.
- Use <%= params %> at the bottom of your page to see what values are present in the params hash.
- You will be using the “.has_key?” method in your code. How might you use the .fetch method? There are many ways to accomplish this assignment using html and ruby.
- Can you populate some of the default values without using conditional logic? Where will you have to use if/else or unless/else blocks?
- Use your browser’s “View Source” option to inspect the HTML that is generated. This is a good way to make sure the HTML is valid.

## Submitting

1. Add all files to your repository using *git add ..*
2. Commit all your changes *git commit -am 'add your commit message here'*
3. Push you changes to github with *git push origin master*
4. Tag your project with *git tag completed -am 'another message'
5. Push your tag to github git push --tags
