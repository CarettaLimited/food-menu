# ordr-menu [![Build Status](https://build.caretta.co.uk/buildStatus/icon?job=ordr-menu)](https://build.caretta.co.uk/job/ordr-menu/)

This project is a food menu and ordering system for restaurants, cafes and takeaways. This project was started in May 2016.

Originally it was envisaged as a replacement for the traditional waiter/menu type of ordering in certain establishments.
A customer can wave their mobile device over a NFC / QR Code and can then order, re-order and pay direct on their mobile device without the need to attract attention of a staff member.
The order is then sent directly to the kitchen.

The current purpose of the project is to allow me to explore new and emerging technologies and apply it to a real world example that is simple for everyone to understand.
I also believe that this can be acheived using a browser on a mobile device without the need for a dedicated mobile app for every restaurant in the world.

The server side components are a [RESTful API](https://en.wikipedia.org/wiki/Representational_state_transfer) built using Node.JS and utilizing [Loopback](http://loopback.io/).
This should allow me to scale up (if ever required!) and allow any device to interact with the data.

I plan to build the frontend using progressive enhancement as well as experiment with different technologies.

Therefore it is planned that the system will be developed in stages as follows:

1. HTML / CSS only - To see if its possible to implement a usuable system with no javascript  <--- In Progress

2. with OO JS - To add enhancements like AJAX and validations for better UX. No JQuery!

3. with Angular

4. with Angular & React

5. With React & React Router

6. with Web Components (Polymer?)


I also plan to:
- Follow Accessibility guidelines throughout. 
- Make it as lightweight and performant as possible 
- Do some performance analysis at every stage.


Further developments may include:
- Look at possible uses of [Service Workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
- Look at using with [The Physical Web](https://google.github.io/physical-web/)
 

Please see the following links for further information.

[Menu Demo](https://ordr.mobi)

[API Explorer](http://api.ordr.mobi/explorer/)

[API GitHub Project](https://github.com/CarettaLimited/ordr-menu-api)

Further Documentation to follow.

Contact me @CarettaDev or mark@caretta.co.uk if you would like to contribute or suggest ideas and improvements