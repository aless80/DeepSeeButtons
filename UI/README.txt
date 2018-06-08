Import DeepSeeButtons and the project in this directory. It contains three %DeepSee.UI.* classes:

%DeepSee.UI.DeepSeeButtonsViewer.cls
%DeepSee.UI.DeepSeeButtonsDownload.cls
%DeepSee.UI.Dialog.GetCubeList.cls

Then navigate to 
http://localhost:57774/csp/samples/_DeepSee.UI.DeepSeeButtonsViewer.zen

Adding a permanent link to SMP > DeepSee is easy. Do that by adding the following three lines to the %DeepSee.UI.Application.cls class above the line with this text: "ADMIN SUB-MENU"

  // ALE's DeepSeeButtons Viewer
  Set tUse = $System.Security.Check("%DeepSee_Admin","USE")|| $System.Security.Check("%Development","USE")
  Set tDisabled = 'tUse
  set tText = $$$Text("DeepSeeButtons Viewer")
  set pData(n,$i(n2)) = $lb($$$Text("DeepSeeButtons Viewer"),tText,..Link("_DeepSee.UI.DeepSeeButtonsViewer.cls"),tDisabled,..Link("deepsee/lamp_48.gif"),tText)