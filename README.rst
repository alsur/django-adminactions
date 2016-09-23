===================
django-adminactions
===================

.. image:: https://badges.gitter.im/Join%20Chat.svg
   :alt: Join the chat at https://gitter.im/saxix/django-adminactions
   :target: https://gitter.im/saxix/django-adminactions?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge


Collection of useful actions to use with
django.contrib.admin.ModelAdmin and/or django.contrib.admin.AdminSite

Please see the changelog at http://django-adminactions.readthedocs.org/en/latest/changes.html

SRJ9 branches
======
* SRJ9/paths: Includes all commits done by SRJ9 based on saxix/develop (Aug 10 2016).
The next branches are composed of saxix/develop (Aug 10 2016) + minimal a few SRJ9/paths commits
* SRJ9/css: Changes CSS style in merge templates.
* SRJ9/filters: Adding custom filters to mass_update and merge (common or individual filters)
* SRJ9/mass-parents: Modify mass_update to append parent operation methods to inherit field
* SRJ9/m2m-other-part: add to merge:m2m the m2m relations defined in the other part of m2m relation
* SRJ9/m2m-apply: passing m2m param to api.merge in apply step
* SRJ9/m2m-alter: adding add_items and remove_items to M2M fields in mass_update
* SRJ9/m2m-onetoonefield: fix many_to_many relations defined in OneToOneField

Actions
=======

* Export as CSV
* Export as Excel
* Export as fixture
* Export delete tree
* Mass update records
* Graph queryset
* Merge records


Project links
-------------

+--------------------+----------------+--------------+-------------------------+
| Stable             | |master-build| | |master-cov| |                         |
+--------------------+----------------+--------------+-------------------------+
| Development        | |dev-build|    | |dev-cov|    |                         |
+--------------------+----------------+--------------+-------------------------+
| Project home page: |https://github.com/saxix/django-adminactions             |
+--------------------+---------------+-----------------------------------------+
| Issue tracker:     |https://github.com/saxix/django-adminactions/issues?sort |
+--------------------+---------------+-----------------------------------------+
| Download:          |http://pypi.python.org/pypi/django-adminactions/         |
+--------------------+---------------+-----------------------------------------+
| Documentation:     |https://django-adminactions.readthedocs.org/en/latest/   |
+--------------------+---------------+--------------+--------------------------+



.. |master-build| image:: https://secure.travis-ci.org/saxix/django-adminactions.png?branch=master
                    :target: http://travis-ci.org/saxix/django-adminactions/

.. |master-cov| image:: https://codecov.io/github/saxix/django-adminactions/coverage.svg?branch=master
    :target: https://codecov.io/github/saxix/django-adminactions?branch=develop


.. |dev-build| image:: https://secure.travis-ci.org/saxix/django-adminactions.png?branch=develop
                  :target: http://travis-ci.org/saxix/django-adminactions/

.. |dev-cov| image:: https://codecov.io/github/saxix/django-adminactions/coverage.svg?branch=develop
    :target: https://codecov.io/github/saxix/django-adminactions?branch=develop
