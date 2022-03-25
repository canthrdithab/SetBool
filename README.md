# SetBool
MsgBox("", $dDouble, "Double has been updated to " &amp; $dDouble &amp; ". Met condition needed and left sleep function") Func SetName()     $sName = "InunoTaishou"     HotKeySet("{F1}", SetBool) EndFunc Func SetBool()     $sBool = False     HotKeySet("{F1}", SetInt) EndFunc
