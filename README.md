# Laravel-Test-Cases
You can learn how to create and run test classes in laravel using PHPunit.

Step 1 : Install Laravel using official documentation.

Step 2 : Create Your actions and then test your actions using Test Case feature provided by Laravel Framework.

Step 3 : How to use Test Case Feature in your project follow the below url.
         
         https://laravel.com/docs/5.0/testing
         
Step 4 : Simple Test Case Example mention as below 

         - First go through above link so you get more idea about TestCase. 
         
         - Create Test file in app/tests directory from your root directory of project.
         
         - Copy below code in created file with name of UserTest.php
         
                  class UserTest extends TestCase {
                  }
                  
         - Test Case is parent class which provide by laravel to create your test case.
         - You have to extends TestCase class in your Test class so you can test your actions test.
         - Example : 
                  public function testloginUser(){
         		$response = $this->call('GET', 'users/show');
         		$this->assertTrue(true);
         	}
         
Step 5 : Go to Commmand Prompt to run this Test Case.

Step 6 : Run the "phpunit" command to run the created test cases.

Step 7 : You will get Response if you success to run all test cases 
         
         - OK (4 tests, 4 assertions) 

         
