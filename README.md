Materials for MicroService Workshop

* Booster 2014 in Bergen, Norway
* GOTO Chicago 2014

http://rubybunny.info/
http://www.rabbitmq.com/install-homebrew.html


== Execution

    brew install rabbitmq
    rabbitmq-server
      #Admin: guest
      #Password: guest

    rabbitmqctl list_users

    ruby rental_offer/rental_offer_need.rb 127.0.0.1 guest
    ruby rental_offer/rental_offer_monitor.rb 127.0.0.1 guest
