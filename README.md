# Assignment Project

> Project setup in local machine
-   Clone project from `git url`
-   Open project in a Code Editor as a `Maven` Project
-   Build the project
-   Navigate to `src>main>java>com.crm.qa>utilities` package, open `TesUtils.java` file
    -    Update the worksapce path in your local machine for `WORKSPACE_PATH` String
- Input file input data update
    -  Navigate to `src>main>java>com.crm.qa>config` package, open `config.properties` file, update following variable values:
        - `url` -> Change URl value to navigate expected website
        - `browser` -> Pass chrome for Chrome browser OR FF for Firefox browser
        - `LeavingFrom` -> Update value for defining Departure place
        - `GoingTo` -> Update value for defining Arrival place
        - `DepartureDate` -> Update value for defining Departure Date (Follow M/DD/YYYY Date format)
        - `ReturnDate` -> Update value for defining Return Date (Follow M/DD/YYYY Date format)

> Steps to run Automation Suite
-   Follow above mentioned points in `Project setup in local machine` section
-   Navigate to src>main>resources, Run `testng.xml`