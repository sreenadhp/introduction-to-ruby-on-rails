> [<< 4. Write the User Story](step-4-write-user-story.md)

> [>> 6. Defining Routes](step-6-first-route.md)


### Write the First Request Spec

Let us first create a new folder under /spec named
requests

##### What are request specs ?
request specs are written while develop a controller request

> Create file '/api/v1/books_spec.rb'

![1](images/code/request_spec_1.png)

Let us run it

`$ rspec spec/requests/api/v1/books_spec.rb`

![1](images/results/request_spec_result_1.png)

Let us inspect the error

`No route matches [GET] "/api/v1/books.json"`

Why? Because we haven't defined routes

> [<< 4. Write the User Story](step-4-write-user-story.md)

> [>> 6. Defining Routes](step-6-first-route.md)
