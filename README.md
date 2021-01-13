# How to test a Terraform Configuration? 

It's possible to write tests using an existing test framework (such as RSpec for Ruby, unit test for Python, etc) which gather relevant resource ids or addresses from the Terraform state file and then use the relevant platform's SDK to retrieve data about the resources and assert that they are set up as expected. This is a more general form of the previous idea, running the tests from the perspective of a host outside of the infrastructure under test, and can thus collect a broader set of data to make assertions on.


<>
