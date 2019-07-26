Get-ChildItem -Path 'ex: C:\' | Sort-Object LastAccessTime -Descending | Select-Object -First 10
