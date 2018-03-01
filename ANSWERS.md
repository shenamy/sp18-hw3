## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?

The second parameter of the text_field_tag is the value. You don't want anything there because that's where the user will put in the value. 

2. Go to `localhost:3000/teachers` in your browser; why does this not work?

There is no route that matches GET "/teachers", so it result in an error. There is only a route for a POST request, which creates /teachers only when a form is submitted. 

3. What type of request did your browser just perform?

Attempted a get request. 

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?

localhost:3000/teachers

5. Why does `localhost:3000/teachers` work now?

Because it is /teachers is a POST request, and the site has been created now from submitting the form, so a page shows up. 
