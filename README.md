# learning-log



## Activate the virtual environment
`cd` into the project directory. The enter `source ll_env/bin/activate` into the terminal

## Viewing the project
Enter the following in a separate terminal:
`python manage.py runserver`

## Steps to add a page
1. In the main project folder open *urls.py*. In urlpatterns add the URLs for the app you created. Make sure to import include from django.urls
2. Add a *urls.py* file in the app folder
3. Add a view in the project *views.py* file
4. Write a template in the templates folder. If you haven't already add a templates folder and a folder inside that folder that shares the app name. Templates should go here.