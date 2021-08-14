# Topo4Edge
Topology data for edge computing networks

## File structure
- `TOPO_NAME`:
    - `TOPO_NAME.jpg` : network graph
    - `graph.txt`     : network graph data (edge-list format: [i, j, bandwidth])
    - `ingress.txt`   : ingress nodes

**Notice**:
Topology `CittaStudi` is generated based on the data from [**OpenCellID**](https://www.opencellid.org/), which is an open database of cell towers. The Città Studi area around Politecnico di Milano is considered. The others are random topologies generated with different numbers of nodes and edges.
