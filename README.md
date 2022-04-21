# RunGroops
Rungroops is an online platform for runners. Find clubs, schedule events, and meet other runners in your area.

[Link](https://rungroops.azurewebsites.net/)

## Get project working
[Youtube video on how to get database setup](https://www.youtube.com/watch?v=af_tK9LUiX0)

1. Go into directory where you plan on keeping project and run.

```bash
  git clone https://github.com/teddysmithdev/RunGroop.git
```

2. Create a local database. (If you are unsure how to do this, watch my Youtube video )


3. Add connection string to app settings.json. It will look something like this:
```bash
  Data Source=DESKTOP-EI2TOGP\\SQLEXPRESS;Initial Catalog=RunGroops;Integrated Security=True;Connect Timeout=30;Encrypt=False;TrustServerCertificate=False;ApplicationIntent=ReadWrite;MultiSubnetFailover=False
```
4. Register for a [Cloudinary Account](https://cloudinary.com/users/register/free) (%100 free) and add Cloudname, ApiKey, and Api secret to appsettings.json.