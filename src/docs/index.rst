..
.. Copyright 2018, Rambler Digital Solutions
..
.. Licensed under the Apache License, Version 2.0 (the "License");
.. you may not use this file except in compliance with the License.
.. You may obtain a copy of the License at
..
.. http://www.apache.org/licenses/LICENSE-2.0
..
.. Unless required by applicable law or agreed to in writing, software
.. distributed under the License is distributed on an "AS IS" BASIS,
.. WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
.. See the License for the specific language governing permissions and
.. limitations under the License.
..

Welcome to airflow-declarative's documentation!
===============================================

:Documentation: https://airflow-declarative.readthedocs.io/
:Source Code: https://github.com/rambler-digital-solutions/airflow-declarative
:Issue Tracker: https://github.com/rambler-digital-solutions/airflow-declarative/issues
:PyPI: https://pypi.org/project/airflow-declarative/


Airflow Declarative allows to define Airflow DAGs declaratively
with YAML.

An example of a simple declarative DAG:

.. code-block:: yaml

    dags:
      my_dag:
        args:
          start_date: 2019-07-01
        operators:
          my_operator:
            class: airflow.operators.dummy_operator:DummyOperator


.. toctree::
   :maxdepth: 2
   :caption: Contents:

   intro
   reference


Indices and tables
==================

* :ref:`genindex`
* :ref:`search`
