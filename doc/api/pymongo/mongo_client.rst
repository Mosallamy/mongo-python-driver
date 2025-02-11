:mod:`mongo_client` -- Tools for connecting to MongoDB
======================================================

.. automodule:: pymongo.mongo_client
   :synopsis: Tools for connecting to MongoDB

   .. autoclass:: pymongo.mongo_client.MongoClient(host='localhost', port=27017, document_class=dict, tz_aware=False, connect=True, **kwargs)

      .. automethod:: close

      .. describe:: c[db_name] || c.db_name

         Get the `db_name` :class:`~pymongo.database.Database` on :class:`MongoClient` `c`.

         Raises :class:`~pymongo.errors.InvalidName` if an invalid database name is used.

      .. autoattribute:: event_listeners
      .. autoattribute:: topology_description
      .. autoattribute:: address
      .. autoattribute:: primary
      .. autoattribute:: secondaries
      .. autoattribute:: arbiters
      .. autoattribute:: is_primary
      .. autoattribute:: is_mongos
      .. autoattribute:: max_pool_size
      .. autoattribute:: min_pool_size
      .. autoattribute:: max_idle_time_ms
      .. autoattribute:: nodes
      .. autoattribute:: local_threshold_ms
      .. autoattribute:: server_selection_timeout
      .. autoattribute:: codec_options
      .. autoattribute:: read_preference
      .. autoattribute:: write_concern
      .. autoattribute:: read_concern
      .. automethod:: start_session
      .. automethod:: list_databases
      .. automethod:: list_database_names
      .. automethod:: drop_database
      .. automethod:: get_default_database
      .. automethod:: get_database
      .. automethod:: server_info
      .. automethod:: watch
