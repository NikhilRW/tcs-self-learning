# TCS JFLAP Self-Learning Assignment

**Student:** Nikhil Ramesh Wankhede  
**Roll No.:** 66  
**Class:** D12C  
**Subject:** Theory of Computer Science (TCS)

## Contents

| No. | Topic | JFLAP file |
|---:|---|---|
| 01 | DFA Construction | [`66_Nikhil_Ramesh_Wankhede_DFA.jff`](66_Nikhil_Ramesh_Wankhede_DFA.jff) |
| 02 | NFA Construction | [`66_Nikhil_Ramesh_Wankhede_NFA.jff`](66_Nikhil_Ramesh_Wankhede_NFA.jff) |
| 03 | NFA to DFA Conversion | [`66_Nikhil_Ramesh_Wankhede_NFAtoDFA.jff`](66_Nikhil_Ramesh_Wankhede_NFAtoDFA.jff) |
| 04 | DFA Minimization | [`66_Nikhil_Ramesh_Wankhede_DFAMinimization.jff`](66_Nikhil_Ramesh_Wankhede_DFAMinimization.jff) |
| 05 | DFA to Regular Grammar | [`66_Nikhil_Ramesh_Wankhede_DFAtoRG.jff`](66_Nikhil_Ramesh_Wankhede_DFAtoRG.jff) |
| 06 | DFA to Regular Expression | [`66_Nikhil_Ramesh_Wankhede_DFAtoRE.jff`](66_Nikhil_Ramesh_Wankhede_DFAtoRE.jff) |
| 07 | Combine Finite Automata | [`66_Nikhil_Ramesh_Wankhede_CombineFA.jff`](66_Nikhil_Ramesh_Wankhede_CombineFA.jff) |
| 08 | Regular Expression | [`66_Nikhil_Ramesh_Wankhede_RE.jff`](66_Nikhil_Ramesh_Wankhede_RE.jff) |
| 09 | RE to DFA Conversion | [`66_Nikhil_Ramesh_Wankhede_REtoDFA.jff`](66_Nikhil_Ramesh_Wankhede_REtoDFA.jff) |
| 10 | RE Identities | [`66_Nikhil_Ramesh_Wankhede_REIdentities.jff`](66_Nikhil_Ramesh_Wankhede_REIdentities.jff) |
| 11 | Regular Grammar | [`66_Nikhil_Ramesh_Wankhede_RegGrammar.jff`](66_Nikhil_Ramesh_Wankhede_RegGrammar.jff) |
| 12 | RG to DFA Conversion | [`66_Nikhil_Ramesh_Wankhede_RG2DFA.jff`](66_Nikhil_Ramesh_Wankhede_RG2DFA.jff) |
| 13 | Context-Free Grammar | [`66_Nikhil_Ramesh_Wankhede_CFG.jff`](66_Nikhil_Ramesh_Wankhede_CFG.jff) |
| 14 | CFG to PDA Conversion | [`66_Nikhil_Ramesh_Wankhede_CFG2PDA.jff`](66_Nikhil_Ramesh_Wankhede_CFG2PDA.jff) |
| 15 | Pushdown Automata | [`66_Nikhil_Ramesh_Wankhede_PDA.jff`](66_Nikhil_Ramesh_Wankhede_PDA.jff) |
| 16 | PDA to CFG Conversion | [`66_Nikhil_Ramesh_Wankhede_PDAtoCFG.jff`](66_Nikhil_Ramesh_Wankhede_PDAtoCFG.jff) |
| 17 | Turing Machine | [`66_Nikhil_Ramesh_Wankhede_TM.jff`](66_Nikhil_Ramesh_Wankhede_TM.jff) |
| 18 | Linear Bounded Automata | [`66_Nikhil_Ramesh_Wankhede_LBA.jff`](66_Nikhil_Ramesh_Wankhede_LBA.jff) |
| 19 | LL Parsing | [`66_Nikhil_Ramesh_Wankhede_LLParsing.jff`](66_Nikhil_Ramesh_Wankhede_LLParsing.jff) |
| 20 | LR Parsing | [`66_Nikhil_Ramesh_Wankhede_LRParsing.jff`](66_Nikhil_Ramesh_Wankhede_LRParsing.jff) |

## How to run

1. Install and launch JFLAP 7.x.
2. Open each `.jff` file through **File > Open**.
3. Run sample inputs using the corresponding menu: **Input > Fast Run / Multiple Run**, **Convert**, **Minimize**, or **Parse** (options vary by model).
4. Record screenshots of the original model, conversion results, and test inputs. Save these under `screenshots/` and update the report.

## Important notes

- Files are original teaching examples; they are **not screenshots from JFLAP**.
- DFAtoRG, DFAtoRE, REtoDFA, NFAtoDFA, CFG2PDA and PDAtoCFG contain constructed **target representations**; perform the conversion in JFLAP if your instructor expects screenshots of each conversion step.
- `LBA.jff` is a **one-tape TM illustration** of a linear-space marking strategy; JFLAP does not guarantee that its tape is mechanically bounded. The supplied model is for demonstration and requires validation, especially on boundary and rejection cases.
- The DFA Minimization example has an unreachable state q3. Remove unreachable states as part of minimization.
- The `REIdentities.jff` file shows the left side of `0+1 = 1+0`; compare it to the right side in JFLAP.
- For LL/LR parsing, open the grammar and invoke the corresponding parser rather than treating the file as a saved parse table.
- Validate the `.jff` models in your installed JFLAP version before submitting.

## Screenshot checklist

For each topic, capture the JFLAP window showing the model and one successful input. For conversion topics, also capture the conversion or resulting model. Avoid using screenshots from others' repositories.
