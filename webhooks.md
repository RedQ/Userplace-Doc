# Webhooks

**We have a dedicated video tutorial for configuring webhook and you can see it from the below URL.**

[https://www.youtube.com/watch?v=VbPBeZAJ3Vg](https://www.youtube.com/watch?v=VbPBeZAJ3Vg)

Webhooks configuration is the most important part for the plugin. If you don't configure the webhooks then the local invoices won't be generated. So after configuring the payment gateway and plan configure the webhooks.

## Webhooks Stripe

For stripe webhooks configuration go to your stripe dashboard `Developer->Webhooks` \([https://dashboard.stripe.com/test/webhooks/](https://dashboard.stripe.com/test/webhooks/)\) In this portion you can add webhooks check the below image.

![](/assets/webhooks.png)

Click on Add endpoint in the top right corner. The you will get a window with something like below image. Here URL to be called is the url which you will get from your wordpress Dashboard Admin Menu `Userplace->Payments`  general submenu. Here Copy the url you get in the below  image pointed url.

![](/assets/webhooks3.png)![](/assets/webhooks2.png)Now check the pointed portion in the images. Now you are done.

_**NB: After configuring the webhooks please send a test webhooks it will complete the webhooks setup.**_

# Configure Webhooks in localhost

To properly configure webhooks in localhost you can use Ultrahooks. Follow the [this](https://praxent.com/blog/testing-webhooks-locally-with-ultrahook "this") tutoral.

# 



