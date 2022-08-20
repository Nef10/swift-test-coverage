# swift-test-coverage

Small Command Line Tool to display the test coverage of a swift package.

## Installation

The tool can be installed via brew: `brew install Nef10/tap/swift-test-coverage`.

## Usage

Just call `swift test-coverage` from a folder within your swift package to see a report with the coverage percentage of the different files.

Call `swift test-coverage show` to aditionally print the coverage of the individual lines or `swift test-coverage export` to export it to an HTML file. The last two options take an optional argument of the relative or absolute filepath to limit printing/exporting the line coverage to this specific file.
