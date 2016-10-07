# PythonTreasure
Treasuregram practice app

Setup
  - $ git clone git@github.com:gus07ven/PythonTreasure.git
  - $ cd PythonTreasure
  - $ mkvirtualenv myenv
  - (myenv) $ pip install -r requirements.txt

Run
  - (myenv) $ python manage.py runserver
  - (myenv) $ python manage.py createsuperuser


To run django shell_plus and view Treasure objects
  - (myenv) $ python manage.py shell_plus
  - In [1]: treasures = Treasure.objects.all()
  - In [2]: print treasures[0].name
  - In [3]: print treasures[0].img_url
