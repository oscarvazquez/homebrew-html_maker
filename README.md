Simple command line html creator

setup 
brew tap oscarvazquez/homebrew-html_maker \n
brew install --HEAD html_maker

to run 
html 
To create a form
html form first_name:text last_name:text email:email password:password date_of_birth:date
All the parameters after form are going to be turned into inputs for the form, the text after the the colon is going to specify 
what type of input you wan't to create

Then you can go on to specify if you wan't a front_end framework like bootstrap or foundation.
