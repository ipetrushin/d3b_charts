# d3b_charts

Data presentation tools for microbial ecology.

## Description

The software is implemented as a web appication based on Django framework.
The format of input data is compatible with Biological Observation Matrix (BIOM) format.
The interactive vizulalization tools are implemented with the use of D3.js software library.

Most of the functionality specific to microbial ecology is implemented with the use of scikit-bio python package, 
in the conjunction with other python packages intended to be used in big data analysis.

## Installation

package should be available as python2 package
consider use virtualenv to install the package

run '...' to download 2-nd party software

## Usage

Run web server by command 'runserver.sh' and open page 'localhost:8000' in the browser.

Upload the data file on a start page of the application. This will create the link to a page with unique identifier.
The interactive tools for the provided data table become available from that link.

Use links on a start page for a several sample data series to test the service.
