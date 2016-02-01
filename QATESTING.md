# QA Testing 

##Types Of Testing 

#### Fn-Functional Testing

#### Automated Testing

#### Ux-Usability Testing

#### Sc-Security Testing

#### Ln-Localization Testing

#### Ld-Load Testing

Scenario execution Process

After completing and validating the script in the VuGen with enhancement and making sure the script passes succeussfully the next step is to take it to the controller and satrt the run. Here are some tips on the steps to follow while running in the controllor.

0. Debug Run: Initially you run the test with 1 user and see if it passes successfully.
0. Then increase the user to 3-5 and see if that passes or not. The purpose of Debug run is to see the responsiveness of the site under very low stress and to validate the business process function is taking the right data that you have assigned to each Vuser. By doing this you will be abale to validate the different enhancement that you had done to the script and if it is working as you had expected to work. This type of test is also called concurrency test where you are trying to examine wheather one or more user can run concurrently from the controlller.
0. After the above scenarios runs successfully then you are ready to execute the sctual test on the controller. But, remember not to run the full load (100%) at once and stressing the sysyem. Initially start with 20-25 % of load first so that you will be able to find if there is some bottleneck at this stage so that you do not have to keep guessing at what point the bottleneck lies. Most importantly, there is no point running with full load when the system  even cannot handle 20-25% of load. See if the system can handle this load without any issues. If there is some issues then try to find out the bottleneck and get back to the team and nad discuss about the bottleneck and try to fix it by collaborating with different memmers of the team and try to solve the issue.
The main goal of this type of testing is to figure out the slowest transactions. This kind of test allows to find bottlenecks and helps you to find main problem areas. If the test runs succussfully then follow the next steps.

