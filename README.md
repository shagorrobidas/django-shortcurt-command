# django-shortcurt-command

## 1. Open your shell config file
```
 nano ~/.bashrc
```
### For zsh (if you're using Oh My Zsh or zsh):
```
nano ~/.zshrc
```
## 2. Add these aliases at the bottom:
``` # Django shortcuts
alias pmr="python manage.py runserver"
alias pmm="python manage.py makemigrations"
alias pmi="python manage.py migrate"
alias pms="python manage.py shell"
alias pmc="python manage.py createsuperuser"
alias pmt="python manage.py test"
alias pma="python manage.py add_user"
```

3. Save and exit
 - Press `Ctrl + O`, then Enter to save
 - Press `Ctrl + X` to exit
