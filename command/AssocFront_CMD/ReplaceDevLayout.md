# Debug Cmd

set  memberContent="D:\HLProject\LocalRelease\AssocFrontShow\AssocFrontShowDebug\\_MemberContent.cshtml"
set login=" D:\HLProject\LocalRelease\AssocFrontShow\AssocFrontShowDebug\Index.cshtml "
set layoutOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Shared\"
set loginOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Home\"
xcopy "%layout%" "%layoutOp%" \/s\/y
xcopy "%login%" "%loginOp%" \/s\/y

