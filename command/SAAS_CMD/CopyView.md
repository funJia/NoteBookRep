#Debug Cmd

@echo off

goto start

= 可以是多行文本，可以是命令

= 可以包含重定向符号和其他特殊字符

= 只要不包含 :start 这一行，就都是注释

:start

set generalMg="D:\HLProject\Develop\SaaS\HLSteward.GeneralMg\Views"

set checkstandMg="D:\HLProject\Develop\SaaS\HLSteward.CheckstandMg\Views"

set dataStatisticsMg="D:\HLProject\Develop\SaaS\HLSteward.DataStatisticsMg\Views"

set financeMg="D:\HLProject\Develop\SaaS\HLSteward.FinanceMg\Views"

set memberMg="D:\HLProject\Develop\SaaS\HLSteward.MemberMg\Views"

set messageCenterMg="D:\HLProject\Develop\SaaS\HLSteward.MessageCenterMg\Views"

set productMg="D:\HLProject\Develop\SaaS\HLSteward.ProductMg\Views"

set signupMg="D:\HLProject\Develop\SaaS\HLSteward.SignupMg\Views"

set venueMg="D:\HLProject\Develop\SaaS\HLSteward.VenueMg\Views"

set output="D:\HLProject\LocalRelease\SaaSMg\SaaSBuildDebug\Views\"

set excludeStr="D:\HLProject\ReleaseBatch\AssocWebSite\EXCLUDE.txt"

xcopy "%generalMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%checkstandMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%dataStatisticsMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%financeMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%memberMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%messageCenterMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%productMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%signupMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

xcopy "%venueMg%" "%output%" \/exclude:D:\HLProject\ReleaseBatch\SaaSMg\EXCLUDE.txt \/s\/y

echo succeed

pause&exit

# Release Cmd

