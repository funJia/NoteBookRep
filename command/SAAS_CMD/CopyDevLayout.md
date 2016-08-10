#Debug Cmd

set layout="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Build\_Layout2.cshtml"

set login="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Build\Login.cshtml"

set layoutOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Shared\"

set loginOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Home\"

xcopy "%layout%" "%layoutOp%" /s/y

xcopy "%login%" "%loginOp%" /s/y



#Release Cmd
set layout="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildRelease\Build\_Layout2.cshtml"

set login="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildRelease\Build\Login.cshtml"

set layoutOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildRelease\Views\Shared\"

set loginOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildRelease\Views\Home\"

xcopy "%layout%" "%layoutOp%" /s/y

xcopy "%login%" "%loginOp%" /s/y



