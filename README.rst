NeoComplCache-UltiSnips
=======================

This is a NeoComplCache extension that provides UltiSnips integration. It adds UltiSnips snippets to NeoComplCache completion and properly sets mappings for correct snippet expanding and jumping.

Installation
------------

Use your preferred way to install plugins. For Vundle, add this to ``.vimrc``:

.. code-block:: vim

    Bundle 'JazzCore/neocomplcache-ultisnips'


Usage
-----

This plugin loads automatically, so you dont need to set any options.

Mappings for snippet expanding and jumping are set on ``g:UltiSnipsExpandTrigger`` key. This means that you can use one key for expanding and jumping but keep in mind that you also can use standard UltiSnips keys, defined by ``g:UltiSnipsJumpForwardTrigger`` and ``g:UltiSnipsJumpBackwardTrigger`` options.
