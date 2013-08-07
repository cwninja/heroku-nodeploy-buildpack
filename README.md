# heroku-nodeploy-buildpack - A buildpack that doesn't work.

* Do you have an app?
* Do you have an app that you don't want to deploy over?
* Do you wish there was some way to stop drunk you from shipping to production?

You should use my broken build pack! (Now with over 100% extra nonfunctionality!)

Usage:

    $ heroku config:set BUILDPACK_URL=https://github.com/cwninja/heroku-nodeploy-buildpack.git

Now when you push to heroku, it won't work.

    $ git push heroku master
    Counting objects: 746, done.
    Delta compression using up to 4 threads.
    Compressing objects: 100% (478/478), done.
    Writing objects: 100% (670/670), 161.08 KiB, done.
    Total 670 (delta 466), reused 290 (delta 191)
    
    -----> Fetching custom git buildpack... done
    -----> Deployment disabled app detected
    -----> Deployment disabled
    
    !     Push rejected, failed to compile Deployment disabled app
    $

Simply configure, sit back, relax, and embrance the broken nature of the world around you.
