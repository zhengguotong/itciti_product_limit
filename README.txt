

"Itciti product limit" is a module on top of Drupal Commerce that allows administrators and other product maintainers
to set a maximum order quantity for any product.

This module will therefore aid in the process of enforcing "1 item per customer" restrictions or similar.
By default any product will have no maximum order quantity. Checks will be done every time the cart is updated using
one of the standard forms.The code of this project is derived from Commerce Stock.

This project is based on a drupal Sandbox Project "Commerce Product limit"(https://www.drupal.org/sandbox/RSpliet/1268568),
This project fix bugs of this sanbox project and extend same new feature includes
1.validate maximum order quantities for commerce cart form, so when customer update product quantities in shopping cart form
  system will also check the new product quantity against the maximum order quantity for each product.
