 cd C:\Users\sofa2\PycharmProjects\PythonProject3
 
python assembler.py test_input.xml test_output.bin test_log.xml
python interpreter.py test_output.bin result.xml 0 100
 
coverage run --source=test_assembler -m test_assembler
coverage run --source=test_mod_operation -m test_mod_operation 