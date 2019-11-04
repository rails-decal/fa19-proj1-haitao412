# Q0: Why are these two errors being thrown?
    pending migrations error causes by old database. Fixed by update the schema.
    Uninitialized constant HomeController::Pokemon caused by the Pokemon model need to be created.

# Q1: How are the random Pokemon appearing? What is the common factor between all the possible Pokemon that appear? *
    Command rails db:seed seeds the the random Pokemon to the database. 

# Question 2a: What does the following line do "<%= button_to "Throw a Pokeball!", capture_path(id: @pokemon), :class => "button medium", :method => :patch %>"? Be specific about what "capture_path(id: @pokemon)" is doing. If you're having trouble, look at the Help section in the README.
    
    Capture the pokemon base on the id of the pokemon. And the catcher is the trainer that current logged in. We using the capture_path to allocate the the id of the pokemon that the current trainer need to catch.
# Question 3: What would you name your own Pokemon?
    
    FreddyCervantes
# Question 4: What did you pass into the redirect_to? If it is a path, what did that path need? If it is not a path, why is it okay not to have a path here?
    Redirect_to the trainer_path. It requires the trainer id since we need to go to one specific trainer's path.

# Question 5: Explain how putting this line "flash[:error] = @pokemon.errors.full_messages.to_sentence" shows error messages on your form.
    
    Handle all errors from the pokemon and print out as sentences.

# Give us feedback on the project and decal below!
    
    None
# Extra credit: Link your Heroku deployed app
    
    I will do it when I get time.