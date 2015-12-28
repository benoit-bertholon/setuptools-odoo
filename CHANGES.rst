Changes
~~~~~~~

(unreleased)
------------
- [ADD] make_pkg_name public api to convert an addon name to a python 
  package name

- [ADD] make_pkg_requirement public api to obtain a valid package requirement
  for a given addon (same as make_pkg_name but includes requirement
  for the correct Odoo series)

- [FIX] crash in case a previous commit had a bad `__openerp__.py`

0.9.0 (2015-12-13)
------------------
- first beta