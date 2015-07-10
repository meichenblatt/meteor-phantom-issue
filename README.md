# meteor-phantom-issue
This repository was created to report a bug to meteor

All I did was create a new app, added spiderable and gadicohen:phantomjs. I kept the meteor's defualt code. I'm getting an 
that they are not connecting. Below is a copy and paste from my command line so you can see the exact steps I took and the 
error.

C:\Users\meich_000\Documents\GitHub> git clone https://github.com/meichenblatt/meteor-phantom-issue.git
Cloning into 'meteor-phantom-issue'...
warning: You appear to have cloned an empty repository.
Checking connectivity... done.
C:\Users\meich_000\Documents\GitHub> cd meteor-phantom-issue
C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue [master]> meteor create sample
sample: created.

To run your new app:
  cd sample
  meteor
C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue [master +1 ~0 -0 !]> cd sample
C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue\sample [master +1 ~0 -0 !]> meteor
[[[[[ C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue\sample ]]]]]

=> Started proxy.
=> Started MongoDB.
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.

Terminate batch job (Y/N)? Y
C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue\sample [master +1 ~0 -0 !]> meteor add spiderable

Changes to your project's package version selections:

spiderable  added, version 1.0.7


spiderable: Makes the application crawlable to web spiders
C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue\sample [master +1 ~0 -0 !]> meteor add gadicohen:phantomjs

Changes to your project's package version selections:

gadicohen:phantomjs  added, version 0.0.2


gadicohen:phantomjs: phantomjs installation script; wrapper for node phantomjs package + Sun
C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue\sample [master +1 ~0 -0 !]> meteor
[[[[[ C:\Users\meich_000\Documents\GitHub\meteor-phantom-issue\sample ]]]]]

=> Started proxy.
=> Started MongoDB.
=> Started your app.

=> App running at: http://localhost:3000/
   Type Control-C twice to stop.

I20150710-09:56:20.762(-7)? spiderable: phantomjs failed: { [Error: spawn ENOENT] code: 'ENOENT', errno: 'ENOENT', sysca
ll: 'spawn' }
I20150710-09:56:20.764(-7)? stderr:
