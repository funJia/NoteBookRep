# Debug Cmd

set memberContent="D:\HLProject\LocalRelease\AssocFrontShowDebug\_MemberContent.cshtml"

set memberContentTop="D:\HLProject\LocalRelease\ AssocFrontShowDebug\_MemberContentTop.cshtml"

set newsActContent="D:\HLProject\LocalRelease\ AssocFrontShowDebug\_NewsActContent.cshtml"

set registerContent="D:\HLProject\LocalRelease\ AssocFrontShowDebug\_RegisterContent.cshtml"

set index="D:\HLProject\LocalRelease\ AssocFrontShowDebug\Index.cshtml"

set memberContentOp="D:\HLProject\LocalRelease\AssocFrontShowDebug\_MemberContent.cshtml"
set memberContentTopOp="D:\HLProject\LocalRelease\ AssocFrontShowDebug\_MemberContentTop.cshtml"
set newsActContentOp="D:\HLProject\LocalRelease\ AssocFrontShowDebug\_NewsActContent.cshtml"
set registerContentOp="D:\HLProject\LocalRelease\ AssocFrontShowDebug\_RegisterContent.cshtml"
set indexOp="D:\HLProject\LocalRelease\ AssocFrontShowDebug\Index.cshtml"

xcopy "%memberContent%" "% memberContentOp%" \/s\/y

xcopy "%memberContentTop%" "%  memberContentTop %" \/s\/y

xcopy "%newsActContent %" "%  newsActContent %" \/s\/y

xcopy "%registerContent  %" "%  registerContent %" \/s\/y

xcopy "%index%" "%  index %" \/s\/y

# Release Cmd

set memberContent="D:\HLProject\LocalRelease\AssocFront\_MemberContent.cshtml"

set memberContentTop="D:\HLProject\LocalRelease\AssocFront\_MemberContentTop.cshtml"

set newsActContent="D:\HLProject\LocalRelease\AssocFront\_NewsActContent.cshtml"

set registerContent="D:\HLProject\LocalRelease\AssocFront\_RegisterContent.cshtml"

set index="D:\HLProject\LocalRelease\AssocFront\Index.cshtml"

set layoutOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Shared\"

set loginOp="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\Home\"

xcopy "%layout%" "%layoutOp%" \/s\/y

xcopy "%login%" "%loginOp%" \/s\/y

