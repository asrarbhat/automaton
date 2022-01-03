# automaton

python script to execute given command <= everytime size of a given file changes,hence everytime a file is modified.(almost)

**download automaton.py**

bash command

wget https://github.com/asrarbhat/automaton/releases/download/v1.0.0/automaton.py

**put it in the same directory as where you are working**

**to execute run**

   * python3 automaton.py "./main.c" "gcc ./main.c && ./a.out"
   * python3 automaton.py "./index.js" "node ./index.js"
   * sky is the limit with what you can do with this
   
**now everytime you make changes to main.c or index.js, it will compile and run automatically, even errors won't terminate it**

**ideally one would split screen into two parts and keep this running in one**
