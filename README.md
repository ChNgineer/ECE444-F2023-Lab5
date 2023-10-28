# ECE444-F2023-Lab5
This repo is a replay of https://github.com/mjhea0/flaskr-tdd

# First Test

![Alt text](images/test1.png)

![Alt text](images/test1_pass.png)

# Database Tests

![Alt text](images/test2.png)

![Alt text](images/test2_pass.png)

# Templates and Views + Login Tests

![Alt text](images/test3.png)

![Alt text](images/test3-1.png)

![Alt text](images/test3_pass.png)

# JavaScript Implementation Tests

![Alt text](images/test4_pass.png)

# SQLAlchemy Tests

![Alt text](images/test5_pass.png)

# Login Required Final Test

![Alt text](images/test6_pass.png)

# Project 1 Group Unit Test

All unit tests under TestEmail are written by me.
https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/blob/chen-dev/api/utils/unit_tests/mailing_test/mailing_test.py#L24-91

If the previous link does not work, it is because the branch has been merged and squashed. If the previous link works, this one should be ignored.
https://github.com/ECE444-2023Fall/project-1-web-application-design-group22-premium-potatoes/blob/main/api/utils/unit_tests/mailing_test/mailing_test.py#L24-91

![Alt text](images/potato_test_snippet.png)

![Alt text](images/potato_test_pass.png)

# Pros and Cons of TDD

The benefits of TDD stem from its incremental nature and modularity. Mapping objectives to functional components and further dividing said components into bite-sized tasks helps developers focus on implementation and the interactions of their respective component relative to its immediate interfacing services and functions in the architecture. This speeds up the pace of development as it becomes increasingly clear what the scope of each increment needs to be and how it can be achieved in a timely manner. TDD also ensures that said interfacing components function as expected individually, easing the process of debugging and troubleshooting, as most errors would likely occur in how each service compartment interacts with another.

The weaknesses of TDD stem from its testing requirements for metric representation of heuristics. TDD is limited by the scope of its testing procedure and the quality of tests written. If poor test cases are designed, then poor code will follow suit. Passing unit tests may not be reflective of real world applications and use cases for the code, as test cases and mocks are determined by developers which hold a bias to the quality of their code. The requirement for writing tests for functionality also add incredible overhead for objectives with dynamic and constantly chanigng needs, as new tests need to be conceptualized from abstract ideas which may take considerable time. It is also important to note that developers will have incredibly difficulty quantifying metrics for testing of heuristics (like user satisfaction) instead of traditional  measurements.