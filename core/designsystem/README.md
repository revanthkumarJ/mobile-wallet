### Module Graph

```mermaid
%%{
  init: {
    'theme': 'neutral'
  }
}%%

graph LR
  subgraph :core
    :core:designsystem["designsystem"]
    :core:model["model"]
  end
  :core:designsystem --> :core:model
```
# :core:designsystem module
## Dependency graph
![Dependency graph](../../docs/images/graphs-kmp/dep_graph_core_designsystem.svg)
