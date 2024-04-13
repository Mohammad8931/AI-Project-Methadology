Usage
=====

This section explains how to run the churn prediction model developed for RetailGenius.

Running the Model
-----------------

1. Ensure all installations and setups are complete as described in the Installation section.

2. Navigate to the script directory:

.. code-block:: bash

   cd path/to/model/script

3. Run the prediction script:

.. code-block:: bash

   python predict_churn.py

This script will load the trained Random Forest model, apply it to the input data, and output the churn predictions.

Interpreting Outputs
--------------------

The output will include a list of customers predicted to churn along with their probabilities. Details on how to interpret and utilize these predictions for strategic business decisions will also be provided.
