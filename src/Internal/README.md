# The internal namespace

All the code in this directory (and hence in the `Automattic\WooCommerce\Internal` namespace) is internal WooCommerce infrastructure code and not intended to be used by plugins. The important thing that this implies is that **backwards compatibility of the public surface for classes in this namespace is not guaranteed in future releases of WooCommerce**.

So if you are a plugin developer, please **never use classes in this namespace directly in your code**. See [the README file for the src folder](https://github.com/woocommerce/woocommerce/blob/master/src/README.md#the-internal-namespace) for more detailed guidance.
