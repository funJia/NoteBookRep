# Debug Cmd

set layout="D:\HLProject\LocalRelease\AssocFrontShow\AssocFrontShowDebug\Index.cshtml"
set login="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Build\Login.cshtml"
set layoutOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Shared\"
set loginOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Home\"
xcopy "%layout%" "%layoutOp%" \/s\/y
xcopy "%login%" "%loginOp%" \/s\/y

