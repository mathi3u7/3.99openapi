* Add support for new value `setup_intent_mobile_wallet_unsupported` on enums `Invoice.last_finalization_error.code`, `PaymentIntent.last_payment_error.code`, `SetupAttempt.setup_error.code`, `SetupIntent.last_setup_error.code`, and `StripeError.code`
* Remove support for `shipping_details` on `Checkout.Session`
* Remove support for `carrier`, `phone`, and `tracking_number` on `Checkout.Session.collected_information.shipping_details`
* Change `Checkout.Session.collected_information.shipping_details.address`, `Checkout.Session.collected_information.shipping_details.name`, `Checkout.Session.collected_information.shipping_details`, and `Checkout.Session.collected_information` to be required
* Remove support for `plan` and `price` on `InvoiceItem`
* Change `PaymentIntent#confirm.payment_method_options.wechat_pay.client`, `PaymentIntent#create.payment_method_options.wechat_pay.client`, and `PaymentIntent#update.payment_method_options.wechat_pay.client` to be optional
* Remove support for `cancel_at_period_end` on `Subscription#create` and `Subscription#update`
* Add support for `wifi` on `Terminal.Configuration#create`, `Terminal.Configuration#update`, and `Terminal.Configuration`
* Add support for new values `2025-03-01.dashboard` and `2025-03-31.basil` on enum `WebhookEndpoint#create.api_version`