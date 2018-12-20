# Pricing Plan

By default pricing plan shortcode page is being created in the plugin activation process. But if you need to configure the page with your own feature. Use the following code.

```php
[userplace_pricing_wrapper]
[userplace_pricing_plan title="Free" best_choice="" amount="$0" cycle="monthly" column="two"]
<ul>
<li>Feature One</li>
<li>Feature Two</li>
<li>Feature Three</li>
<li>Feature Four</li>
</ul>
[userplace_plan_button class="button" plan_id="default"]
[/userplace_pricing_plan]
[userplace_pricing_plan title="Premium" best_choice="" amount="$10" cycle="monthly" column="two"]
<ul>
<li>Feature One</li>
<li>Feature Two</li>
<li>Feature Three</li>
<li>Feature Four</li>
<li>Cancel anytime</li>
</ul>
[userplace_plan_button class="button" plan_id="premium"]
[/userplace_pricing_plan]

[/userplace_pricing_wrapper]
```

The main thing here is that, you must add the **userplace\_pricing\_wrapper** shortcode and the inside of it **userplace\_pricing\_plan **shortcode.

Inside the **userplace\_pricing\_plan **you can add any HTML and another important thing is **userplace\_plan\_button **shortcode.

This shortcode returns the plan page URL. Make sure that you have provided the stripe plan id here.

