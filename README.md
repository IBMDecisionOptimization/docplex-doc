# IBM® Decision Optimization Modeling for Python (DOcplex)

Welcome to the IBM® Decision Optimization Modeling for Python.
Licensed under the Apache License v2.0.

With this library, you can quickly and easily add the power of optimization to
your application. You can model your problems by using the Python API and solve
them on the cloud with the IBM® Decision Optimization on Cloud service or on
your computer with IBM® ILOG CPLEX Optimization Studio.

This library is composed of 2 modules:

* IBM® Decision Optimization CPLEX Optimizer Modeling for Python - with namespace docplex.mp
* IBM® Decision Optimization CP Optimizer Modeling for Python - with namespace docplex.cp

Solving with CPLEX locally requires that IBM® ILOG CPLEX Optimization Studio V12.8.0
is installed on your machine.

Solving with the IBM Decision Optimization on Cloud service requires that you
register for an account and get the API key.

This library is numpy friendly.

## Install the library

```
   pip install docplex
```

## Get the documentation and examples

* [Documentation](http://ibmdecisionoptimization.github.io/docplex-doc/)
* [Examples](https://github.com/IBMDecisionOptimization/docplex-examples)

## Get your IBM® Decision Optimization on Cloud API key

Optionally, you can run your optimization in the cloud with the IBM
Decision Optimization on Cloud service.
   
- Register for the DOcplexcloud free trial and use it free for 30 days. See [Free trial](https://developer.ibm.com/docloud/try-docloud-free).
 
- Get your API key
    With your free trial, you can generate a key to access the DOcplexcloud API. 
    Visit the [Get API key & base URL](http://developer.ibm.com/docloud/docs/api-key) page to generate the key once you've registered. 
    This page also contains the base URL you must use for DOcplexcloud.
    
- Copy/paste your API key and service URL where appropriate in the examples to be able to run them, or have a look at *Setting up an optimization engine* section of the documentation

## Get your IBM® ILOG CPLEX Optimization Studio edition

- You can get a free [Community Edition](http://www-01.ibm.com/software/websphere/products/optimization/cplex-studio-community-edition)
 of CPLEX Optimization Studio, with limited solving capabilities in term of problem size.

- Faculty members, research professionals at accredited institutions can get access to an unlimited version of CPLEX through the
 [IBM® Academic Initiative](http://www-304.ibm.com/ibm/university/academic/pub/page/ban_ilog_programming).

## Dependencies

These third-party dependencies are automatically installed with ``pip``

- [docloud](https://pypi.python.org/pypi/docloud)
- [enum34](https://pypi.python.org/pypi/enum34)
- [futures](https://pypi.python.org/pypi/futures)
- [requests](https://pypi.python.org/pypi/requests)
- [six](https://pypi.python.org/pypi/six)

## License

This library is delivered under the  Apache License Version 2.0, January 2004 (see LICENSE.txt).
