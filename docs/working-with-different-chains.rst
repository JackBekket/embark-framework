Working with different chains
=============================

You can specify which environment to deploy to:

``$ embark blockchain production``

``$ embark run production``

The environment is a specific blockchain configuration that can be
managed at config/blockchain.json

.. code:: json

    # config/blockchain.json
      ...
       "livenet": {
        "networkType": "livenet",
        "rpcHost": "localhost",
        "rpcPort": 8545,
        "rpcCorsDomain": "http://localhost:8000",
        "account": {
          "password": "config/production/password"
        }
      },
      ...
