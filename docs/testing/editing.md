==================================================
TEST ID:        1
TEST SCENARIO:  Try to edit task with valid data
TEST STEPS:     Go to the Task list page => press Edit task => enter test data => click Edit task
TEST DATA:      Title: Study harder
                Deadline: 2019-12-31
EXPECTED RESULT:Message says that the task was edited
ACTUAL RESULT:  Message said that the task was edited
PASS/FAIL:      Pass

==================================================
TEST ID:        2
TEST SCENARIO:  Try to edit task with invalid data
TEST STEPS:     Go to the Task list page => press Edit task => enter test data => click Edit task
TEST DATA:      Title: un existed note
                Deadline: 2019-12-31
EXPECTED RESULT:Message says that the task was not found
ACTUAL RESULT:  Message said that the task was not found
PASS/FAIL:      Pass
