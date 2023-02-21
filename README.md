# Jmeter_Load_Test_Example

An example project of Jmeter load testing on [Demoblaze](https://www.demoblaze.com/).

### Setup
* Install **Java 8+**
* Download [Jmeter](https://jmeter.apache.org/download_jmeter.cgi)(Jmeter 5.5 was used to create the script)

### Running Tests

* Run tests with generation **HTML** report
  ```
  ./jmeter.sh -n -t "<full-path-to-project>/demoblaze.jmx" -l "<full-path-to-project>/Result.csv" -e -o "<full-path-to-project>/Reports"
  ```
* Open **index.html** in Reports folder to see the results.
