# DeepSeeButtons
Script used by the DeepSee support group at InterSystems to gather system information. 

### Installation

Manually download or clone this repository.  
Import DeepSeeButtons.xml or DeepSeeButtons.mac to the %SYS namespace or to any namespace running DeepSee. The DeepSeeButtons.mac file uses the new UDL formatting, which should work on IS IRIS and Caché version above 2016.1. 

### Running DeepSeeButtons

Launch DeepSeeButtons from terminal as:

`%SYS>Do ^DeepSeeButtons`

Then follow the prompts. 

![Alt Text](https://github.com/aless80/DeepSeeButtons/blob/master/HowTo.gif)

### Inspecting DeepSeeButtons reports

The script outputs a a report in html format. You can inspect DeepSeeButtons reports in any browser, though I recommend using Chrome or Firefox. 
This repository includes an example, DeepSeeButtonsExample.html, which you can open using this link: [https://rawgit.com/aless80/DeepSeeButtons/master/DeepSeeButtonsExample.html](https://rawgit.com/aless80/DeepSeeButtons/master/DeepSeeButtonsExample.html)

### Notes

Please ignore the UI folder in this repository, which contains an implementation to allow running DeepSeeButtons from a page in the IS IRIS/Caché Management Portal. 