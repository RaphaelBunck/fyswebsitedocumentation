.. _installation:

Installation
============

Here we wil give instructions on how to install our website and hardware
programs.

Website Installation
--------------------
First clone the project and run the installation commands: ::

    git clone git@gitlab.fdmci.hva.nl:TI102_FYS1/Website.git
    npm install
    npm start

This will run on http://localhost:3000
You need to have mongodb running, we don't add placeholder users by default so
you need to register first at /user/register.

.. warning::
    The FYS website is also running at http://62.251.28.9:3000. You can use the following
    account for testing purposes:
    Email: raphaelbunck@gmail.com
    Password: 123

Skynet
------

Skynet is our python program that handles all hardware interactions.
To install clone the repo and run the script: ::

    git clone git@gitlab.fdmci.hva.nl:TI102_FYS1/Skynet.git
    python2 gui2.py

This probably won't run, because you need to have all hardware attachments
plugged in the same slots as we have.

We've included a couple of pictures for instruction purposes:

.. image:: ../images/PI2.jpeg
    :width: 45%

.. image:: ../images/NFC.jpeg
    :width: 45%



