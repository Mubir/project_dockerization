        1.creating a django project:
        after writing Dockerfile and docker-compose file run
        $$      sudo docker-compose run web django-admin startproject noob .

        2.change permission if needed:

        $$    sudo chown -R user_name: .

        3.create a app:
        keep the compose up
        then
        $$      docker container exec id/name_of_container python manage.py startapp name_of_app
