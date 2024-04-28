#tittle<br>
    Step1: 
        Q -->GPT (reconstruct the query)-->Q1
    step2: 
        Q1 -->google scholar api -->top 20 results (connecting tittle and abstract)--list    compute similarity with Q1
    step3:
        return top 10 results --> classify to get 3-5 types
    step4:
        users choose, can see the paper and abstract
    Step5: 
        decision tree:
            if type correct, paper correct, terminate and return the paper
            if tpype correct, paper incorrect, reconstruct the Q1 based on the type info and get Q2, go the step 2



