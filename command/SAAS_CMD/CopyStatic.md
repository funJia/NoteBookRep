# Debug Cmd
@echo off

set assets="D:\HLProject\Develop\SaaS\HLSteward.Web\assets"

set comDevl="D:\HLProject\Develop\SaaS\HLSteward.Web\Component"

set components="D:\HLProject\Develop\SaaS\HLSteward.Web\components"

set content="D:\HLProject\Develop\SaaS\HLSteward.Web\content"

set content="D:\HLProject\Develop\SaaS\HLSteward.Web\Build"

set configs="D:\HLProject\Develop\SaaS\HLSteward.Web\configs"

set data="D:\HLProject\Develop\SaaS\HLSteward.Web\Data"

set configTxt="D:\HLProject\Develop\SaaS\HLSteward.Web\config.txt"

set output="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\"

set newOutput="%output%assets\"

xcopy "%assets%" "%newOutput%" /s/y

set newOutput="%output%Component\"

xcopy "%comDevl%" "%newOutput%" /s/y

set newOutput="%output%components\"

xcopy "%components%" "%newOutput%" /s/y

set newOutput="%output%content\"

xcopy "%content%" "%newOutput%" /s/y

set newOutput="%output%configs\"

xcopy "%configs%" "%newOutput%" /s/y

set newOutput="%output%Build\"

xcopy "%configs%" "%newOutput%" /s/y

set newOutput="%output%Data\"

xcopy "%data%" "%newOutput%" /s/y

xcopy "%configTxt%" "%output%" /s/y

echo succeed

pause


# Release Cmd

@echo off

set assets="D:\HLProject\Develop\SaaS\HLSteward.Web\assets"

set comDevl="D:\HLProject\Develop\SaaS\HLSteward.Web\Component"

set components="D:\HLProject\Develop\SaaS\HLSteward.Web\components"

set content="D:\HLProject\Develop\SaaS\HLSteward.Web\content"

set content="D:\HLProject\Develop\SaaS\HLSteward.Web\Build"

set configs="D:\HLProject\Develop\SaaS\HLSteward.Web\configs"

set data="D:\HLProject\Develop\SaaS\HLSteward.Web\Data"

set configTxt="D:\HLProject\Develop\SaaS\HLSteward.Web\config.txt"

set output="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildRelease\"

set newOutput="%output%assets\"

xcopy "%assets%" "%newOutput%" /s/y

set newOutput="%output%Component\"

xcopy "%comDevl%" "%newOutput%" /s/y

set newOutput="%output%components\"

xcopy "%components%" "%newOutput%" /s/y

set newOutput="%output%content\"

xcopy "%content%" "%newOutput%" /s/y

set newOutput="%output%configs\"

xcopy "%configs%" "%newOutput%" /s/y

set newOutput="%output%Build\"

xcopy "%configs%" "%newOutput%" /s/y

set newOutput="%output%Data\"

xcopy "%data%" "%newOutput%" /s/y

xcopy "%configTxt%" "%output%" /s/y

echo succeed

pause


