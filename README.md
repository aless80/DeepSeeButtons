# DeepSeeButtons
Script used by the DeepSee support group at InterSystems to gather system information. 

### Installation

Manually download or clone this repository.  
Import DeepSeeButtons.xml or DeepSeeButtons.mac to the %SYS namespace or to any namespace running DeepSee. The DeepSeeButtons.mac file uses the new UDL formatting, which should work on IS IRIS and Caché version above 2016.1. 

### Running DeepSeeButtons

Launch DeepSeeButtons from terminal as:

`%SYS>Do ^DeepSeeButtons`

Then follow the prompts. 

![Alt Text](https://github.com/aless80/DeepSeeButtons/blob/master/HowTo.gif =250x)

### Inspecting DeepSeeButtons reports

The script outputs an html file similar to DeepSeeButtonsExample.html included in this repo. You can see DSbuttons.html in your browser at this link: [https://rawgit.com/aless80/DeepSeeButtons/master/DeepSeeButtonsExample.html](https://rawgit.com/aless80/DeepSeeButtons/master/DeepSeeButtonsExample.html)

### Notes

Please ignore the UI folder in this repository, which contains an implementation to allow running DeepSeeButtons from a page in the IS IRIS/Caché Management Portal. 