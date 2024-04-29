# Government patterns

An open repository for Finnish and Russian verb government patterns. 

## Syntax

Rules for arguments and object generally follow a key-value syntax.

* `HEAD`: The key for specifying part-of-speech, this key also allows to match a phrase.
  * `POS`: A key for specifying part-of-speech but only for a single word.
* `Case`: A key for case
* `Gov_Case`: A key of Prepositional phrase for specifying the case of the prepositional phrase governs

### Example

`HEAD:Noun + Case:Genitive + Dependency_Type:obl`: A noun phrase in genitive case with `obl` dependency type.

`HEAD:Preposition + Base:за + Gov_Case:Accusative`: A prepositional phrase governs accusative noun phrase and its preposition is за.

## Citation

```
@inproceedings{a20ec44386594643a3ab4504535a45a4,
  title = "What do Transformers Know about Government?",
  author = "Jue Hou and Anisia Katinskaia and Lari Kotilainen and Sathianpong Trangcasanchai and {Vu Anh}, Duc and Roman Yangarber",
  year = "2024",
  language = "English",
  booktitle = "Proceedings of the 2024 Joint International Conference on Computational Linguistics, Language Resources and Evaluation (LREC-COLING 2024)",
}
```
