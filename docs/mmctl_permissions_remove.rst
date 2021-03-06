.. _mmctl_permissions_remove:

mmctl permissions remove
------------------------

Remove permissions from a role (EE Only)

Synopsis
~~~~~~~~


Remove one or more permissions from an existing role (Only works in Enterprise Edition).

::

  mmctl permissions remove <role> <permission...> [flags]

Examples
~~~~~~~~

::

    permissions remove system_user list_open_teams
    permissions remove system_manager sysconsole_read_user_management_channels

Options
~~~~~~~

::

  -h, --help   help for remove

Options inherited from parent commands
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

::

      --config-path string           path to the configuration directory. If "$HOME/.mmctl" exists it will take precedence over the default value (default "$XDG_CONFIG_HOME")
      --format string                the format of the command output [plain, json] (default "plain")
      --insecure-sha1-intermediate   allows to use insecure TLS protocols, such as SHA-1
      --local                        allows communicating with the server through a unix socket
      --strict                       will only run commands if the mmctl version matches the server one

SEE ALSO
~~~~~~~~

* `mmctl permissions <mmctl_permissions.rst>`_ 	 - Management of permissions

