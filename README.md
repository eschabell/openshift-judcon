JUDCon Boston mobile registration app on OpenShift
====================================================

This is the JUDCon Boston 2012 html5/mboile registration app.

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Create a jbossas-7 application

    rhc app create -a judcon -t jbossas-7 --from-code git://github.com/eschabell/openshift-judcon.git

That's it, you can now checkout your application at:

    http://judcon-$namespace.rhcloud.com

Don't forget it is better in your mobile browsers!
