=====
AdminLTE
=====

AdminLTE is a Django app to conduct Web-based frontend theme. This is not replace your admin however you
can build admin like functionality in frontend.

Quick start
-----------

1. Add "adminlte" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...
        'polls',
    ]

2. Add below commands in your settings.py

    SITE_NAME = 'YOUR_SITE_NAME'

3. Include the polls URLconf in your project urls.py like this::

    path('', include('adminlte.urls')),

4. Run ``python manage.py migrate`` to create the adminlte models.

5. Start the development server and visit http://127.0.0.1:8000/
   to create a adminlte (you'll need the Admin app enabled).

6. Visit http://127.0.0.1:8000/polls/ to participate in the poll.