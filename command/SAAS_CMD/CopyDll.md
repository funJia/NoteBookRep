@echo off

set bin="D:\HLProject\Develop\SaaS\HLSteward.Web\bin\AutoMapper.Net4.dll"

set lib="D:\HLProject\Develop\SaaS\HLSteward.Web\Lib"

set output="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\bin\"

xcopy "%bin%" "%output%" /s/y

set output="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Lib\"

xcopy "%lib%" "%output%" /exclude:D:\HLProject\ReleaseBatch\SaaSMg\dll_Exclude.txt /s/y

echo succeed

pause
