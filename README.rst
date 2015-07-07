django-shop-wspay
=================

`WSPay`_ payment gateway implementation for `django-shop`_.

:Version: 0.0.1
:Source: http://github.com/dinoperovic/django-shop-wspay/
:Dev Status: Alpha


Installation
------------

To install with ``pip`` run:

.. code:: bash

    pip install django-shop-wspay

Install from github using pip:

.. code:: bash

    pip install -e git://github.com/dinoperovic/django-shop-wspay.git@master#egg=django-shop-wspay


Configuration
-------------

- Install and configure `django-shop`_.
- Add ``shop_wspay`` to ``INSTALLED_APPS``.
- Add ``shop_wspay.wspay.WSPayBackend`` to ``SHOP_PAYMENT_BACKENDS``.
- Done.



.. _WSPay: http://www.wspay.info/
.. _django-shop: https://github.com/divio/django-shop
