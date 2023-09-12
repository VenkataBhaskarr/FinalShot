## contains Important SQL concepts 
[Refer Here](https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbGNlSkszVVlpSlFscFd1aGQtaFAteVdjWHBjd3xBQ3Jtc0ttZTJMLWlxbk5aVEtDWXAtUE03dURjd24tR01EWG02cVp2UFNTeXp4eWQwOU52V1J6OU54d2cxMzZWbms5ZmNrc0FHTFpSNnFKMjlnQnNPNmdoVWNTWDdRNlhKU09Qd01sX3lPS1lNMlRtRmt0bnoxMA&q=https%3A%2F%2Fdrive.google.com%2Ffile%2Fd%2F1y3KKghRhQjKfbWhvLipMOCCemKd_XdTm%2Fview%3Fusp%3Dsharing&v=dl00fOOYLOM)


# some of the important concepts

## 1. Normalization
  Generally why would one normalize their databases because of to remove redundance and anomolies that might be created in the long run which makes the database inconsistent there are in general 5 NF's but doing until 3 NF's might do the job 99.9percent so lets discuss about them now
  1 NF :
   this is simple which states that no row ordering should present, no composite datatype should present in a column and no multiple values should present in a column
  2 NF :
   this states that every non prime key must depend on entire primary key if it depends partially then they should yeild another table to remove redundancey
  3 NF :
   this states that no transitive dependency should present in between non prime attributes if exists make a separte table of their own
  BCNF :
    this states same as 3NF but it includes all the attributes (i mean in 3NF its only non -prime right!!)


   
## 2. How data is stored in the form of B,B+trees in databases
   before learning b/b+ trees one needs to know what tracks,sectors,blocks in the hard disk later how the data is stored in the blocks later what are indexes later how indexes stores data/pointers later m-type trees later should dive into these b/b+trees

