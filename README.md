| Lean 3         | Lean 4         | requires                            |
| -------------- | -------------- | ----------------------------------- |
| all_goals      | all_goals      | [core]                              |
| any_goals      | any_goals      | [core]                              |
| apply          | apply          | [core]                              |
| assumption     | assumption     | [core]                              |
| by_cases       | by_cases       | [core]                              |
| by_contradiction | by_contra    | import Mathlib.Tactic.ByContra      |
| cases          | cases'         | import Mathlib.Tactic.Cases         |
| congr          | congr          | [core]                              |
| contradiction  | contradiction  | [core]                              |
| contrapose     | contrapose     | import Mathlib.Tactic.Contrapose    |
| convert        | convert        | import Mathlib.Tactic.Convert       |
| convert_to     | convert_to     | import Mathlib.Tactic.Convert       |
| exact          | exact          | [core]                              |
| exfalso        | exfalso        | import Std.Tactic.Basic             |
| field_simp     | field_simp     | import Mathlib.Tactic.FieldSimp     |
| finish         | —              | —                                   |
| have           | have           | import Mathlib.Tactic.Have          |
| hint           | —              | —                                   |
| induction      | induction'     | import Mathlib.Tactic.Cases         |
| intro          | intro          | [core]                              |
| intros         | intro          | [core]                              |
| iterate        | iterate        | import Std.Tactic.Basic             |
| left           | left           | import Mathlib.Tactic.LeftRight     |
| library_search | library_search | import Mathlib.Tactic.LibrarySearch |
| linarith       | linarith       | import Mathlib.Tactic.Linarith      |
| push_neg       | push_neg       | import Mathlib.Tactic.PushNeg       |
| rcases         | rcases         | import Std.Tactic.RCases            |
| refl           | rfl            | [core]                              |
| repeat         | repeat'        | import Std.Tactic.Basic             |
| right          | right          | import Mathlib.Tactic.LeftRight     |
| ring           | ring           | import Mathlib.Tactic.Ring          |
| rintro         | rintro         | import Std.Tactic.RCases            |
| rw             | rw             | [core]                              |
| simp           | simp           | [core]                              |
| sorry          | sorry          | [core]                              |
| specialize     | specialize     | [core]                              |
| split          | constructor    | [core]                              |
| squeeze_simp   | simp?          | import Std.Tactic.SimpTrace         |
| suggest        | library_search | import Mathlib.Tactic.LibrarySearch |
| swap           | swap           | import Mathlib.Tactic.PermuteGoals  |
| symmetry       | symm           | import Mathlib.Tactic.Relation.Symm |
| tauto          | tauto          | import Mathlib.Tactic.Tauto         |
| try            | try            | [core]                              |
| unfold         | unfold         | [core]                              |
| use            | use            | import Mathlib.Tactic.Use           |
