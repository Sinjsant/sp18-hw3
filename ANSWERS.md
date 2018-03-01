## Questions

1. What does the second 'nil' argument in the line 6 text_field_tag of teachers/new.html.erb represent?
The 'nil' argument makes it so that methods that are called on the input always return True.

2. Go to `localhost:3000/teachers` in your browser; why does this not work?
No route matches get '/teachers'.

3. What type of request did your browser just perform?
A get request.

4. Go back to `localhost:3000/teachers/new`; submit the form again. What URL do you end up at?
'localhost:3000/teachers'

5. Why does `localhost:3000/teachers` work now?
It works because when the Create teacher button is clicked on /teachers/new, a post request (which is routed) is made to /teachers.
