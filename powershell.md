Get-ChildItem -Path 'ex: C:\' | Sort-Object LastAccessTime -Descending | Select-Object -First 10


###### Encontrar String específica
 `Get-ChildItem -Path d:\applications\*config -recurse |  Select-String -Pattern "dummy"`
