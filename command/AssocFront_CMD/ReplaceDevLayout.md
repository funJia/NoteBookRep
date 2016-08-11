set memberContent="D:\HLProject\LocalRelease\AssocFrontShowDebug\Build\_MemberContent.cshtml"

set memberContentTop="D:\HLProject\LocalRelease\AssocFrontShowDebug\Build\_MemberContentTop.cshtml"

set newsActContent="D:\HLProject\LocalRelease\AssocFrontShowDebug\Build\_NewsActContent.cshtml"

set registerContent="D:\HLProject\LocalRelease\AssocFrontShowDebug\Build\_RegisterContent.cshtml"

set index="D:\HLProject\LocalRelease\AssocFrontShowDebug\Build\Index.cshtml"

set memberContentOp="D:\HLProject\LocalRelease\AssocFrontShowDebug\Views\Shared\_MemberContent.cshtml"

set memberContentTopOp="D:\HLProject\LocalRelease\AssocFrontShowDebug\Views\Shared\_MemberContentTop.cshtml"

set newsActContentOp="D:\HLProject\LocalRelease\AssocFrontShowDebug\Views\Shared\_NewsActContent.cshtml"

set registerContentOp="D:\HLProject\LocalRelease\AssocFrontShowDebug\Views\Shared\_RegisterContent.cshtml"

set indexOp="D:\HLProject\LocalRelease\ AssocFrontShowDebug\Views\Home\Index.cshtml"

xcopy "%memberContent%" "%memberContentOp%" \/s\/y

xcopy "%memberContentTop%" "%memberContentTopOp%" \/s\/y

xcopy "%newsActContent%" "%newsActContentOp%" \/s\/y

xcopy "%registerContent%" "%registerContentOp%" \/s\/y

xcopy "%index%" "%indexOp%" \/s\/y


