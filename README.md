# parallel-run-on-colab
Take "word count" task for example to show how to complete one task by several pcs on colab.

1. get n pcs on colab;
2. copyt all these files on the 1st one and share them to all the rest of pcs on colab
3. on pc-1: run 'count_word.py' as 'master' mode;
4. on pc-1: run 'count_word.py' as 'slave' mode;
5. on pc-2~n:run 'count_word.py' as 'slave' mode;
