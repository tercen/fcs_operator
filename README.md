# Read FCS operator

##### Description

`read_fcs` operator transforms FCS files to Tercen datasets.

##### Usage

Input projection|.
---|---
`documentId`        | is the documentId (document can be a single FCS file, or a zipped set of FCS files)

Output relations|.
---|---
`filename`          | character, the name of the FCS file
`channels`          | numeric, one variable per channel in the FCS file

##### Details

The operator transforms FCS files into Tercen dataset. If the document is a ZIP file containing a set of FCS files, the operator extracts the FCS files and tranforms them into Tercen datasets.

The Flow Cytometry Standard is a data file standard for the reading and writing of data from flow cytometry experiments.
