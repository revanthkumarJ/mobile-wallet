### Module Graph

```mermaid
%%{
  init: {
    'theme': 'neutral'
  }
}%%

graph LR
  subgraph :core
    :core:common["common"]
    :core:data["data"]
    :core:model["model"]
    :core:datastore["datastore"]
  end
  :mifospay-web --> :mifospay-shared
  :mifospay-web --> :core:common
  :mifospay-web --> :core:data
  :mifospay-web --> :core:model
  :mifospay-web --> :core:datastore
```
# :mifospay-web module
## Dependency graph
![Dependency graph](../docs/images/graphs-kmp/dep_graph_mifospay_web.svg)
