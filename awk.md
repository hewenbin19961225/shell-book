AWK -F ',' '{print $1}' t1.txt
AWK -F ',' 'ARGIND==1{} ARGIND==2{}' t1.txt t2.txt
AWK -F '[,|#]' '{print $1}' t1.txt
