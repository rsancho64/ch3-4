# ch3-4

reducing fake migrations to zero.

Your migration history can shows table already made but unreal.
So following below

`python manage.py migrate --fake sessions zero`<br>
`python manage.py showmigrations`<br>
output : ... [ ] 0001_initial<br>
`python manage.py migrate --fake-initial # then migrate with --fake-initial again`<br>
