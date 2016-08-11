# Debug Cmd

set  memberContent="D:\HLProject\LocalRelease\AssocFront\\_MemberContent.cshtml"
set  memberContentTop="D:\HLProject\LocalRelease\AssocFront\\_MemberContentTop.cshtml"
set  newsActContent="D:\HLProject\LocalRelease\AssocFront\\_NewsActContent.cshtml"
set  registerContent="D:\HLProject\LocalRelease\AssocFront\\_RegisterContent.cshtml"
set index="D:\HLProject\LocalRelease\AssocFront\Index.cshtml"

set layoutOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Shared\"
set loginOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Home\"
xcopy "%layout%" "%layoutOp%" \/s\/y
xcopy "%login%" "%loginOp%" \/s\/y

