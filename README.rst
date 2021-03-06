“Hook” files for PyInstaller
==================================

THIS REPOSITORY IS DEPRECATED. Please see `pyinstaller-hooks-contrib <https://github.com/pyinstaller/pyinstaller-hooks-contrib>`_ instead.
------------------------------------------------------------------------------------------------------------------------------------------
This package includes the “hook” files extending PyInstaller to adapt it to
the special needs and methods used by a Python package.

PyInstaller bundles a Python application and all its dependencies into a single
package. The user can run the packaged app without installing a Python
interpreter or any modules.

.. image:: https://img.shields.io/badge/IRC-pyinstalller-blue.svg
   :target: http://webchat.freenode.net/?channels=%23pyinstaller&uio=d4
   :alt: IRC


:Website:       http://www.pyinstaller.org/
:Documentation: https://pyinstaller.readthedocs.io/en/stable/hooks.html
:Code:          https://github.com/pyinstaller/pyinstaller-hooks


Installation
------------

This package is automatically installed when installing PyInstaller but can be
updated independently of PyInstaller.

PyInstaller-Hooks is available on PyPI. You can update it through `pip`::

      pip install --update pyinstaller-hooks


For more details, see the `manual`_.

.. _`manual`: https://pyinstaller.rtfd.io/en/latest/



License
------------

This package is distributed under the same license as PyInstaller itself:

 Distributed under the terms of the GNU General Public License with exception
 for distributing bootloader.

 The full license is in the file COPYING.txt, distributed with this software.
