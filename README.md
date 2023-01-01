# Analytical-Decision-Models-For-Supply-Chain

Consider the posted folder cs787_ha2_supp_manuf_transp_sn_template folder. 

Install Pyomo package:
https://pyomo.readthedocs.io/en/stable/index.html

Under the subfolder solution, duplicate the Python module ams_template.py into ams.py.
Implement the required analytic models (see below) by filling out ams.py template.

Example inputs and corresponding outputs are given in the folder example_input_output. To run the implemented functions in Problem 1 below, use solution/main.py

a. In terminal, make the downloaded folder your current folder.

b. In main.py uncomment invocation of the function you want to run, 
e.g. answer = ams.supplierMetrics(input) and comment other invocations.

c. Run main.py in Python w/ stdin being the model input, 
e.g., example_input_output/supplier_in.json and indicate the file in stdout

Example: python solution/main.py < example_input_output/supplier_in.json > answers/out.json to get answers in out.json which you can compare with the correct answer, 
e.g., in example_input_output/supplier_out.json.
