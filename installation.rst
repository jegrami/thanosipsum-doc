============
Installation
============

Local Setup (Development)
--------------------------

1. Clone the repository ans change into the project directory:

.. code-block:: bash

    git clone https://github.com/yourusername/thanosipsum.git
    cd thanosipsum

PDM is used for dependency management. Visit the `official website <https://pdm-project.org/latest/>`__ for installation instructions.

Once you have PDM installed, you can set up the project:

2. Install dependencies:

.. code-block:: bash

    pdm install


3. Run the app:

.. code-block:: bash

    pdm run uvicorn app:app --reload


