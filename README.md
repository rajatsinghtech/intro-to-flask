> Written manually, without AI assistance.

# intro-to-flask

## What this does

Learning exercises from picking up Flask â€” routing and templating
experiments plus a complete blog app built by following the official Flask
tutorial.

## Business process

None â€” this is a practice repo. Each file is one small lesson: a route, a
template, a form, then the full request/response/database cycle of a real
( tiny) blog.

## Technical flow

[`quickstart.py`](quickstart.py) is a scratch file of commented experiments
(routing, HTML escaping). [`flask-tutorial/flaskr/`](flask-tutorial/flaskr/)
is the finished tutorial app: `auth.py` (register/login), `blog.py` (CRUD
posts), `db.py` + `schema.sql` (SQLite), Jinja `templates/` and `static/`
assets.

## How to run

From `flask-tutorial/`, follow the official Flask tutorial: initialise the
database, then run the dev server. `quickstart.py` is for reading, not
running â€” most of it is commented out.
