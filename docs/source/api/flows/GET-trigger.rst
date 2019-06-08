Trigger
=======

This operation will begin running the steps within a flow as if it was triggered. None of the triggers attached to a flow are actually involved in this operation.

Requests
--------
.. code-block:: http

    GET /flows/{id}/trigger HTTP/1.1

Parameters
^^^^^^^^^^
``{id}`` is the Guid of the flow to trigger.

Response
--------
