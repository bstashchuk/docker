# Docker Project

Project for the Dockerfiles and Docker Compose sections

## Initial configuration

- Create account at the [unsplash.com]
- At the [https://unsplash.com/oauth/applications] create new **demo** application with title **"Images Gallery"**
- In the newly created application find section **"Keys"** and copy **Access Key**
- In the api folder create file **.env.local** and add there following line:

```
UNSPLASH_KEY=<Paste copied access Key here>
```

EXAMPLE with fake code(don't try to use it in your app):

```
UNSPLASH_KEY=2MJvApIkV13hfg2LmQlneILfHoJ2ttlzSdPKefGOyKM
```
