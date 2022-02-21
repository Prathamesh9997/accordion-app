---
title: Razorpay payment
tags: ['Webdev', 'payment']
image: https://s3.us-west-2.amazonaws.com/secure.notion-static.com/094abe36-fd11-4ee4-8b47-670f679eaa47/Screenshot_from_2022-01-18_17-36-53.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220221T133358Z&X-Amz-Expires=3600&X-Amz-Signature=73e944d431d37c68478502693cdc803f4f2e9ab3b6d0abf0e9c5b9b2139b4a25&X-Amz-SignedHeaders=host&x-id=GetObject
---
# Steps to integrate

* Setting up Razorpay account.

* Storing API keys in settings.py

* Installing Razorpay library.

* Creating order schema.

* Creating order at backend and also creating Razorpay order.

	* Show template

	* Show views

	* render to payment.html

	* info of call back URL

* Making payment.

* Handling payment success and failure.

	* Razorpay makes a post request

	* with the help of that handling success/failure

![](https://s3.us-west-2.amazonaws.com/secure.notion-static.com/9ef0a154-3e34-4e4a-b946-1c681b4cf75a/rpay_medium1.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220221%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220221T133358Z&X-Amz-Expires=3600&X-Amz-Signature=60c0c2194a899d4b6a4edc253d9b787149d89a78eb49dc82e2ba66455307c482&X-Amz-SignedHeaders=host&x-id=GetObject)

