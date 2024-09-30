# learn_linux_by_doing
Task 1
1.I used the command line (rm test-1) to delete test-1 file in data directory.
2. The file top-5-lowest-temparatures.csv was moved to the analyzed directory using the command line (mv top-5-lowest- 
    temparatures.csv analyzed)

3. We used the "sort" command line with options like -k -n -r -t and head -n 5 to specify the seperator type,column number,numerically sorting, sorting in reverse order(highest to lowest) and head -n 10 to limit the output to atleast 10 lines. here's the exact command line used ; sort -t, -k3 -nr satelite_temperature_data.csv| head -n 10
