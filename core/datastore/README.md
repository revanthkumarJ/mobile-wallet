### Module Graph

```mermaid
%%{
  init: {
    'theme': 'neutral'
  }
}%%

graph LR
  subgraph :core
    :core:datastore["datastore"]
    :core:model["model"]
    :core:common["common"]
  end
  :core:datastore --> :core:model
  :core:datastore --> :core:common
```
# :core:datastore module
## Dependency graph
![Dependency graph](../../docs/images/graphs-kmp/dep_graph_core_datastore.svg)
