## The Latest Version

Details of the latest version can be found on the
[JMeter Apache Project web site](https://jmeter.apache.org/)

## Requirements

The following requirements exist for running the demo JMeter test plan:

- The latest [Java JDK](https://www.oracle.com/java/technologies/downloads/) version installed on your local machine.

## Running JMeter

1. Clone this repository to your local machine: `https://github.com/QualityOwl/qowl-demo-jmeter.git`
2. Open the repository folder.
3. Open 'jmeter.bat'
   - *Location --> $\bin\\*
4. Wait for JMeter to open
5. Click 'File > Open'
6. Open 'demo-test-plan.jmx'
   - *Location --> $\test_plans\\*
8. Click 'Run' button

### Windows

For Windows, there are also some other scripts which you can drag-and-drop
a JMX file onto:

- `jmeter-n.cmd` - runs the file as a non-GUI test
- `jmeter-n-r.cmd` - runs the file as a non-GUI remote (client-server) test
- `jmeter-t.cmd` - loads the file ready to run it as a GUI test
