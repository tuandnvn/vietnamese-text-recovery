vietnamese-text-recovery
========================
Author: Tuan Do N. Email tuandn@brandeis.edu
------------------------------------------------------------------------------------------
---- For creating simulating data, use function module_test.py in package data_simulate: -
---- to create non-diacritics data from the test directory. ------------------------------
------------------------------------------------------------------------------------------		
---- For training, use function "test_build_language_model" in module_test in package ---- 
---- train: the model will be saved at data\t1-60.model ----------------------------------
------------------------------------------------------------------------------------------
---- For testing, use function "test_decode_all" in module_test in decode : the result ---
---- is stored in directory data_test_result ---------------------------------------------
------------------------------------------------------------------------------------------
---- Auxiliary data files: ---------------------------------------------------------------
---- abbreviation.txt: format full_form	contract_form	prob 	translation --------------
------------------------------anh		a				0.3		I (you) ------------------