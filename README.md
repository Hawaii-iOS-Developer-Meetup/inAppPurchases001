Swift 3 In App Purchase Tutorial
==============================

Source code on making In App Purchases using Swift 3. 

Tutorial:

https://youtu.be/zRrs7O5yjKI

I presented this code at the Hawaii iOS Developer Meetup on 2017_2_9

Seemu's In-App Purchases tutorial: http://youtu.be/zRrs7O5yjKI

    Register App on itunes connect:
      Create new App ID on developer.apple.com
      Create new app on itunesconnect.apple.com
      Go to new app
      Click on Features tab
      Click on In-App Purchases
      Set up 1 consumable
      Set up 1 non consumable
      Keep track of the identifiers you set up.

    Code the IAP in the project:
      git clone this project
      Update the project with the following
      Update bundle identifier to the app id you just created.
      Copy the iapIdentifiers you set for your consumable and non-consumables
      Paste into the let values in ViewController.swift
        iapIdentifier001 = "<>"

    Test IAP with in-app purchases:
      Set up a test user in your app on itunesconnect
        Use that test users to log in when you click on the button to purchase in your app
        Do this or else you will be charged
    FIN
