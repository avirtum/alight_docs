Namespaces
==========

Every scope and child scopes of it can have own sets of directives, controllers and filters. You should make an object **$ns** in scope. This can resolve conflict of names. This lets create private directives, filters and controllers.

If you want to inherit global directives, you may set **scope.$ns.inheritGlobal** = true.

`Example <http://jsfiddle.net/lega911/9mfpbrw7/>`_

.. raw:: html
   :file: discus.html
