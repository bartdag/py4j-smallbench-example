Py4J Small Benchmark
====================

Small benchmark to help diagnose a Py4J Issue.

To run the Java code:

::

    cd java
    ./gradlew run


To run the Python code:

::

    # in a virtualenv, e.g.,
    # virtualenv ~/py4jsmall
    # source ~/py4jsmall/bin/activate
    cd python
    pip install -r requirements.txt
    python smallbench.py
