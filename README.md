#Braintree Testing

Right-click context menu to fill form elements with Briantree's testing credit cards numbers. Currently Chrome only.
Basically it's a simplified version of [Test Payments](https://github.com/facundofarias/test-payments) but focused on Braintree.

Original fork of [test-payments](https://github.com/facundofarias/test-payments).

<img src="https://lh3.googleusercontent.com/_L5a3WL6h_l14iGb-gkonT11OrWbWbECVT_JgvTTPo45g9zLcWcwcYJ4-VwdBczvu5Gr17pjrg=s1280-h800-e365-rw" width="600" />

##Usage

Install the extension from the [Chrome Web
store](https://chrome.google.com/webstore/detail/braintree-testing/ejnobgjbngckmjfhhgieglmhddcgncil). After
installation, just right-click on any editable item on the page and you'll see the
Braintree Testing submenu. Click an item there, and it will be inserted into the
editable field.


##Features

* Fast access to Braintree test payment data: Successful and Unsuccessful credit cards numbers
* Works on input fields, text areas, content editable DIVs
* Works on multi-frame pages, but only if they are from the same domain
* Only works in Chrome
* Tiny overhead per page (<1k), no 3rd party library dependencies, completely passive, so it does not interfere with your web app execution in any way

##Questions, suggestions

Twitter: [@diego_iglesias](https://twitter.com/diego_iglesias)

##Resources for more info

* [BrainTree Developers Testing](https://developers.braintreepayments.com/reference/general/testing/)

##Credits

Thanks to [@gojkoadzic](http://twitter.com/gojkoadzic) and [@facundofarias](https://twitter.com/facundofarias) for the baseline.
Icons by Font Awesome: http://fortawesome.github.io/Font-Awesome/
