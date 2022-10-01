# Project setup in local machine

1. Clone project from `git url`
2. Open project in a Code Editor as a `Maven` Project
3. Build the project
4. Navigate to `src>main>java>com.crm.qa>utilities` package, open `TesUtils.java` file
   a) Update the worksapce path in your local machine for `WORKSPACE_PATH` String
5. Input file input data update
    a) Navigate to `src>main>java>com.crm.qa>config` package, open `config.properties` file, update following variable values:
        - `url` -> Change URl value to navigate expected website
        - `browser` -> Pass chrome for Chrome browser OR FF for Firefox browser
        - `LeavingFrom` -> Update value for defining Departure place
        - `GoingTo` -> Update value for defining Arrival place
        - `DepartureDate` -> Update value for defining Departure Date (Follow M/DD/YYYY Date format)
        - `ReturnDate` -> Update value for defining Return Date (Follow M/DD/YYYY Date format)

# Steps to run Automation Suite

1. Follow above mentioned points in `Project setup in local machine` section
2. Navigate to src>main>resources, Run `testng.xml`