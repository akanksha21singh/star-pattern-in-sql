# star-pattern-in-sql
set @var=0;<br>
select repeat('*',@var:=@var+1)<br>
from information_schema.tables<br>
limit 5


output:
*<br>
**<br>
***<br>
****<br>
*****<br>
