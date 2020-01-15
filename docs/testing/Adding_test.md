==================================================
TEST ID:        1
TEST SCENARIO:  Try to add task with valid data
TEST STEPS:     Go to the Add Task page =>  enter test data => click Add task
TEST DATA:      Title: Study
                Deadline: 2019-12-31
EXPECTED RESULT:Message says that the task was added  
ACTUAL RESULT:  Message said that the task was added
PASS/FAIL:      Pass

==================================================
TEST ID:        2
TEST SCENARIO:  Try to add task with invalid data
TEST STEPS:     Go to the Add Task page =>  enter test data => click Add task
TEST DATA:      Title:
                Deadline: 2014-12-31
EXPECTED RESULT:Message says that failed to add the task
ACTUAL RESULT:  Message said that failed to add the task 
PASS/FAIL:      Pass
