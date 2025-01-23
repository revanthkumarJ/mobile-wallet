### Module Graph

```mermaid
%%{
  init: {
    'theme': 'neutral'
  }
}%%

graph LR
  subgraph :core
    :core:network["network"]
    :core:common["common"]
    :core:model["model"]
    :core:datastore["datastore"]
  end
  :core:network --> :core:common
  :core:network --> :core:model
  :core:network --> :core:datastore
```
# :core:network module
## Dependency graph
![Dependency graph](../../docs/images/graphs-kmp/dep_graph_core_network.svg)
