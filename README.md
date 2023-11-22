# Device-Farm

**Device Farm in AWS refers to AWS Device Farm, a cloud-based service that allows you to test your mobile apps (Android and iOS) on real devices. This service helps you ensure the quality and performance of your applications across a wide range of devices without the need to own or manage physical devices.**

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Some of the key features of AWS Device-Farming:

*Real Devices:* AWS Device Farm provides access to a large fleet of real devices. This allows you to test your app on a diverse set of devices to ensure compatibility and performance across different screen sizes, operating system versions, and device types.

*Automated Testing:* You can automate your tests using popular testing frameworks like Appium, XCTest, and Espresso. AWS Device Farm supports automated testing for native, hybrid, and mobile web applications.

*Manual Testing:* In addition to automated testing, you can also perform manual testing on real devices. This is useful for exploratory testing and interacting with the app in a more human-like manner.

*Parallel Testing:* Device Farm enables you to run tests in parallel on multiple devices, reducing the overall testing time.

*Remote Access:* You can remotely access devices in the AWS Device Farm fleet. This allows you to interact with devices in real-time, capturing screenshots and video recordings during testing.

*Integration with CI/CD:* AWS Device Farm can be integrated into your continuous integration and continuous deployment (CI/CD) pipeline, allowing you to automatically run tests whenever you make changes to your app.

*Reports and Artifacts:* Device Farm provides detailed test reports, logs, and other artifacts, helping you diagnose issues and improve the quality of your mobile applications.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**Steps to test your application:**
__________________________________________________________________________________________________________________________________________________________________________________________

*Step 1:* First create a project in project Dashboard for automation testing.

*Step 2:* Select an .apk file for Android or .ipa file for IOS devices.

*Step 3:* Upload the respective file,it may take some minutes.

*Step 4:* Select the test type you need to run if u have scripts choose "Built in: Explorer" or choose "Built-in: Fuzz".

*Step 4:* Set the Event Count and Event Throttle count according to your requirement here I have set EV-6000 and ET-50.

*Step 5:* Choose for a Device you need to test,there are various devices available in AWS-Device Farming.I have chosen "Samsung Galaxy Tab S7" to run my application.

*Step 6:* You can also choose DEvice Location for specific behaviour.

*Step 7:* Set Execution Timeout.

*Step 8:* Request for the selected device and wait for few minutes.

*Step 9:* Run the application with that device in the given time slot and exit.

*Step 10:* Check for the detailed report of your session and download it.I have my report uploaded here in *Files* folder.

__________________________________________________________________________________________________________________________________________________________________________________________
