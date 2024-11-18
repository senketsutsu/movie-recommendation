## Describing files
All the files are generated automatically based on the dataset.
1. [cleora input clique](./movielens/cleora_input_clique.txt) ->  This file is an input of form 
```
user_1 movie_1 movie_2
user_2 movie_2 movie_3
```
. This allows for columns in cleora input "complex::reflexive::CliqueNode"
2. [cleora input star](./movielens/cleora_input_star.txt) ->  This file is an input of form 
    ```
    ID1 user_2
    ID1 movie_1
    ID1 movie_2
    ID2 user_2
    ID2 movie_2
    ID2 movie_3
    ```
 This allows for columns in cleora input "transient::cluster_id StarNode"

3. [Train](./movielens/lp_train.txt) and [Test](./movielens/lp_test.txt) contain real edges contained in the graph and are used for evaluation.

