# ECE444-F2023-Lab5
Unit tests written: 
test_events_page_not_logged_in

test_events_page_loads

test_user_profile

test_profile_not_logged_in

test_password_reset

test_reset_password_not_logged_in

TDD: Pros and Cons 
Some of the pros of TDD include a high test coverage, since tests are being written for each individual feature leading to a better quality test suite and therefore fewer defects. It also improves the maintainability and eases the ability to refactor the code due to the decouplement of individual components. As a result, it becomes easier to make changes to a component without affecting the functionality of a different feature. It also significantly reduces the risk of refactoring as there is a quality test suite available to catch any regressions that a code change or improvement creates. It also makes the debugging process more efficient as you can easily isolate features that have bugs due to the comprehensive and decoupled test suite. 

Some disadvantages of TDD include the potential to lengthen the development time since it requires a learning curve to write effective tests and structure the code so that it is easy to test and decoupled from other components. Additionally, it requires incremental increases in the code instead of writing it all upfront which may also contribute to longer development time. It may also lead to over-engineering due to the emphasis on making all the code testable, thus increasing complexity in the actual code. It may also lead to missed code regressions as it relies on the accuracy of the tests written to validate the functionality of the code, so it can provide a false sense of security when the tests themselves have bugs. 
