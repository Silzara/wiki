Screen Sessions
===============

Using GNU Screen to manage persistent server sessions.

.. code-block:: bash

   # Start a new screen session
   screen -S servername

   # List sessions
   screen -ls

   # Reattach to session
   screen -r servername

   # Detach from session
   Ctrl+A then D
