# Linux_learn_dirname
dirname 顯示檔案位置

範例 : 

`log_file=$( lsnrctl status | awk '/Listener Log File/ {print $NF}' )`

`dirname $log_file`
