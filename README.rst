#################
django-shop-wspay
#################

.. image:: https://img.shields.io/travis/dinoperovic/django-shop-wspay.svg
    :target: https://travis-ci.org/dinoperovic/django-shop-wspay
.. image:: https://img.shields.io/pypi/v/django-shop-wspay.svg
    :target: https://pypi.python.org/pypi/django-shop-wspay/


`WSPay`_ payment gateway implementation for `django SHOP <http://www.django-shop.org>`_.

    This project is ment for version 0.2.x of djangoSHOP. If you use djangoSHOP version 0.9.x and above, there's a new project `djangoshop-wspay`_.

============
Installation
============

To install with ``pip`` run:

.. code:: bash

    pip install django-shop-wspay

Install from github using pip:

.. code:: bash

    pip install -e git://github.com/dinoperovic/django-shop-wspay.git@master#egg=django-shop-wspay


=============
Configuration
=============

- Install and configure `django-shop`_.
- Add ``shop_wspay`` to ``INSTALLED_APPS``.
- Add ``shop_wspay.wspay.WSPayBackend`` to ``SHOP_PAYMENT_BACKENDS``.
- Done.


.. _WSPay: http://www.wspay.info/
.. _django-shop: https://github.com/divio/django-shop
.. _djangoshop-wspay: https://github.com/dinoperovic/djangoshop-wspay


=========
Changelog
=========

0.0.2
    + Fix casting approval code to int removes leading zeros.

0.0.1
    + Alpha release
