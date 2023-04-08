# Understand Archi Tool Model File Structure

Archi store the model in one single file with extension `.archimate`, the file is in XML format.

When you start from one empty model, you will have the file as below:

```XML
<?xml version="1.0" encoding="UTF-8"?>
<archimate:model xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance" xmlns:archimate="http://www.archimatetool.com/archimate" name="test2" id="id-61e011e655fb40d3ae25e0473d628c6d" version="5.0.0">
  <folder name="Strategy" id="id-f17cd7312cca4e2ca8bed3f23acd14bd" type="strategy"/>
  <folder name="Business" id="id-26612ea8f7614bbd86cf8d936682fb85" type="business"/>
  <folder name="Application" id="id-756e3ee9ea854f9483cc978658211a4b" type="application"/>
  <folder name="Technology &amp; Physical" id="id-f19682beb0b648bfb36d94b0f49ebe31" type="technology"/>
  <folder name="Motivation" id="id-c634c79bdafe466ab3db9c7d51fbdf13" type="motivation"/>
  <folder name="Implementation &amp; Migration" id="id-f796e5690c4e480bb5302a6296e39764" type="implementation_migration"/>
  <folder name="Other" id="id-c313edf2549d4902ac7932a12dccfa12" type="other"/>
  <folder name="Relations" id="id-e57fe88e5ee74ab3a773bccdd15a0b12" type="relations"/>
  <folder name="Views" id="id-328e09c148be4adb8fc092b461798f2e" type="diagrams">
    <element xsi:type="archimate:ArchimateDiagramModel" name="Default View" id="id-c9bfa834ca0b4b628a3a9adaf47d32a1"/>
  </folder>
</archimate:model>

```

Let's use following steps to examine the model file structure:

1. Add one element
2. Add documentation to element
3. Add properties to element
4. Create a view
5. Add element (instance) to the view
6. Adjust element looks and feels in the view
7. Add relationship between element
8. Add properties to relationship