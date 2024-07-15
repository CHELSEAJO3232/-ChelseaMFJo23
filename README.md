const flashpay = require(flashpay) ('sk_test_BQokikJ0vB12...

await flashpay.paymentIntents.create({

amount: 2000,

currency: 'NGN

});
$ node server.js && flashpay listen > Ready! Waiting for requests...

2024-05-02 06:38:36 [200] payment_intent.created

2624-05-02 06:38:36 [200] charge.succeeded


