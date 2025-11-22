### MediaHub 
media sharing platform that has role based access
    - teacher role
        manage assigned student content
        media ploads
    - student role
        sharing media uploads
    - admin role
        overseeing all content
        managint the platform


### Tools for use
- django as the framework
- python lybraries (ready made snippets for a specific job like bootsrap)
    - pillow : 
        for media transactions in python frameworks (absolute media url ,)
    - cloudinary :
        for media storage and also url access generation (url -> save to the database for an upload)
    - python-decouple :
        media tasks

### Apps in the Projects
- Accounts :
    authentication and authorization (signups, login, forgot password)
- mediaAssets :
    upload tasks , displays , updates

### Steps
- installing the libraries :
    -pip install libraryname
    -pip install -r requirements.txt
- create our apps
- configure our project settings
    - register our apps
    - register cloudinary (give the cloudinary configs)
    - register a custom authentication process
    - emails registry


### authentication and authorization
- Authentication :
    - identity identification ( who are you)
- Authorization :
    - access and usage privilages
        - role based authorisation , token based authorization 

1. Create our custom user model - models.py
2. Extend the integrate from captures - forms.py
3. Create views action for registration and login - views.py

    
