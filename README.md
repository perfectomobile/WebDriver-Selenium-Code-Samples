WebDriver-Selenium-Code-Samples
===============================

This folder contains code samples for the Perfecto Mobile webDriver 

Author      : Uzi Eilon <uzie@perfectomobile.com>

===============================

The components are:

•	MobileTest - main(String[] args) – gets testcase and devices and executed the testcase on the real devices          simultaneously

•	PerfectoMobileBasic  - abstract class which manage the driver and devices for all the test 
      o	BofaApp_app extends PerfectoMobileBasicTest – Example for mobile app test 
      o	PerfectoTestCheckFlight extends PerfectoMobileBasicTes– Example for web app test 

•	ExecutionReporterinterface  - summary report generator  
  o	HTMLReporter implements ExecutionReporter – create an HTML summary report 

