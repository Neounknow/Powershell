**Event Log**
See number of log by category
> Get-EventLog -List

See log list 
> Get-EventLog -LogName Application -Newest 20

See log detail
> (Get-Eventlog -index 910 application).message
