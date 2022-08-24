# ImportError-cannot-import-name-user-from-django.contrib.auth.models
from django.db import models from django.contrib.auth.models import user   #create your models here  class Notes(models.model):     user = models.ForeignKey(user, on_delete=models.CASCADE)
