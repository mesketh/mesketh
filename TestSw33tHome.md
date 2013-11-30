<link href="http://kevinburke.bitbucket.org/markdowncss/markdown.css" rel="stylesheet"></link>
<link rel="stylesheet" href="./tablestyle.css"/>

# Welcome to TestSw33t

## Problem Space
_Ever written web or http/REST services and then unit tested them via SOAPUI only to have to constantly tweak when switching your tests to another hosting environment?_ _Having to change messages and endpoint urls just to check out whether a service is functional and performant or not?_ _It's tedious and error prone but, you wonder what kind of effort you would have to go to JUST to run these things automagically alongside your Jenkins CI build?_

## Solution Space

TestSw33t is a java-based tool that performs the following tasks:
 
*	Runs your existing SOAPUI test suites in a headless mode (using the native _testrunner.bat_ bundled with SOAPUI)
*	Performs property expansion within SOAP messages via the convention of configuring a file named _TestSuiteName_.properties.
*	Allows common properties to be shared and specified _once_ for all Test Suites via the bundled _runner.properties_
*	Aggregates all test suite results and generates a single html report powered by jQuery UI suitable for publishing to a wiki or CI Jenkins build.

### Feature Matrix

<div class="CSSTableGenerator" >
 <table>
<tr><th>Feature</th></tr>
                    <tr>
                        <td>
                            Title 1
                        </td>
                        <td >
                            Title 2
                        </td>
                        <td>
                            Title 3
                        </td>
                    </tr>
                    <tr>
                        <td >
                            Row 1
                        </td>
                        <td>
                            Row 1
                        </td>
                        <td>
                            Row 1
                        </td>
                    </tr>
                    <tr>
                        <td >
                            Row 2
                        </td>
                        <td>
                            Row 2
                        </td>
                        <td>
                            Row 2
                        </td>
                    </tr>
                </table>
      </div>
            