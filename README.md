### Steps to reproduce

1. Clone the repo.
0. Run `docker-compose run --rm app composer install` and then `docker-compose run --rm app composer run prepare` to init project. Port 8000 is used.
0. Go to http://localhost:8000/admin/users - use email / password - `test@example.com` / `test@example.com`
0. Click on the User's table sort or input anything in the search field -- you should see that all model overlays are now visible. 

