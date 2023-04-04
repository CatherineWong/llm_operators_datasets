### Datasets and large file extras for the llm_operators repository.
This contains large datasets and extras. used in the main repository at: https://github.com/CatherineWong/llm-operators 

### ALFRED Linearized Dataset.
This contains a modified subset of the [ALFRED dataset](https://github.com/askforalfred/alfred).

It contains PDDL problem files that involve goals written in a normalized form, which nests multiple `exists` statements and then a conjunction of predicates.
It can be used by unzipping the `alfred_linearized_pddl.zip` directory.
To be used directly with the original commands, the unzipped directory should be located at `llm-operators/data/dataset/alfred_linearized_pddl` with respect to the top-level llm-operators repository. 

### ALFRED Pretrained motion planner.
This contains a compressed version of the trained motion planner used in conjunction with our adapted [ALFRED motion planner model](https://github.com/jiahai-feng/alfred).

It should be decompressed and extracted to `<ALFRED_ROOT>/t5-small-finetuned-alfred-long`.
