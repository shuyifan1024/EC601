# EC601_project3_twitter_test

Project 3 Twitter API Test

This assignment will test the Twitter API in the Project 2 assignment. The test function mainly tests the number of input searches, the content of input keywords, the quantity of output content, the correctness of output content, and the repetition of output content. These test contents are relatively close to the real use from the point of view of product design.


test the input of testing number-'input_number_test' function
 
When we enter the test quantity, we may manually enter the error.  People should have typed a positive number, but they might have typed a letter or some other non-positive number.  This could cause the search to crash.So the first thing in this test program is to test the correctness of the input test quantity.


test the output number-'output_number_test' function

When we call the API to search for relevant information, we need to search 1000 items, and when we get the output, we need to test whether we really get 1000 items of data.  Sometimes there are fewer than 1,000 entries, or there is something wrong with our search program.  That's all we need to test.  So the test program added statistics of the output data.


test the content of output-'output_text_test' function

When we call our API search system, users want to get tweets related to keywords.  If the retrieval system does not search for the keyword, the output is not what the user wants.  Such products are problematic.  So the test system adds a check of the content of the test output.


test the ccr of the API function-'ccr'function
Users use the API to retrieve keyword related data.  We need to test the accuracy of output.  Test if the output contains these keywords.


test repeating content of output -'repeat_test' function

Users use keyword search to quickly search for keyword related tweets.  Users' time is valuable.  They can't waste their time reading repetitive content.  We all know that there are tons of comments in tweets.  Some comments are repeated multiple times.  So we added a test system to determine if the output was duplicated.  This is also designed to address API availability.  Improve the user experience.

