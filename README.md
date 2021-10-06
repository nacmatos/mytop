
# mytop

Script em Perl para apresentar alguns contadores de performance do MySQL  
de forma similar ao "top".  

## Usage
```
$ ./mytop


                        Uptime = 5 day(s), 1 hour(s), 40 min(s) (2021/10/01 10:39:04)
                     Queries/s = 1
             Threads_connected = 1
                  Key_writes/s = 0
          Key_write_requests/s = 0
                   Key_reads/s = 0
           Key_read_requests/s = 0
 (Key_blocks_)used/used+unused = 43.0%
               Key_blocks_used = 370056
             Key_blocks_unused = 489904
                  Com_delete/s = 0 media=---
                  Com_insert/s = 0 media=---
                  Com_update/s = 0 media=---
                  Com_select/s = 0 media=0.0
              Com_set_option/s = 0 media=0.0


     Id     User            Host         DB         Command  Time State           Info
------- -------- --------------- ---------- --------------- ----- --------------- ---------------------------------------------------------------------------
     22     root       localhost      mysql           Query     0 init            show processlist

Threads per host
----------------
localhost       : 1
```

## Author

Nereu Matos - nacmatos  

## License

This project is licensed under the MIT License.  
