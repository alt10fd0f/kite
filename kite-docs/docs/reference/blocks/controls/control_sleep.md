---
sidebar_position: 44
---

import EmbedFlowNode from "../../../../src/components/EmbedFlowNode";
import NodeInfoExplorer from "../../../../src/components/NodeInfoExplorer";

# Wait

<EmbedFlowNode type="control_sleep" />

The `Wait` block pauses the flow execution for a specified amount of time. This is useful for creating delays, rate limiting, or scheduling actions to occur after a certain period. The wait blocks are only allowed to go up to 30 seconds per block, and they may not be stacked to add more time onto it.

<NodeInfoExplorer type="control_sleep" />
