# ONTAP-REST-API
Sample scripts for illustrating the use of ONTAP REST APIs and  ONTAP REST API Python Client Libraries.

# NetApp ONTAP
The Python client library is a package you can use when writing scripts to access the ONTAP REST API. It provides support for several underlying services, including connection management, asynchronous request processing, and exception handling. By using the Python client library, you can quickly develop robust code to support the automation of your ONTAP deployments.

# Getting started
The Python client library is available as the package netapp_ontap at the Python Package Index (PyPi) web site at https://pypi.org/project/netapp-ontap

# Software requirements

Before installing the Python client library, you must make sure the following packages are installed on your system:

python 3.5 or later
requests 2.21.0 or later
marshmallow 3.2.1 or later

# Installing and importing the package

You must install the package using the pip utility:

pip install netapp-ontap

# After installing the package, you can import the objects you need into your application:

from netapp_ontap.resources import Volume, Snapshot
