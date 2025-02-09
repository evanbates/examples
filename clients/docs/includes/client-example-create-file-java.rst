
Create a local file (for example, at ``$HOME/.confluent/java.config``) with
configuration parameters to connect to your |ak| cluster. Starting with one of
the templates below, customize the file with connection information to your
cluster. Substitute your values for ``{{ BROKER_ENDPOINT }}``,
``{{CLUSTER_API_KEY }}``, and ``{{ CLUSTER_API_SECRET }}``
(see `Configure Confluent Cloud Clients <https://docs.confluent.io/cloud/current/client-apps/config-client.html>`__
for instructions on how to manually find these values, or use the :cloud:`ccloud-stack Utility for Confluent Cloud|examples/ccloud/docs/ccloud-stack.html` to automatically create them).

- Template configuration file for |ccloud|

  .. literalinclude:: includes/configs/cloud/java.config

- Template configuration file for local host

  .. literalinclude:: includes/configs/local/java.config
