swarm/
├── glimmer/               # Local Glimmer runner (Q4 4-bit, ~20GB, 20K tok/s)
│   ├── server.py          # llama.cpp / MLX server with speculative DFlash backend
│   └── mcp_manifest.json  # Native MCP tools Glimmer uses
├── prime/
│   └── SELF.md            # The canonical self-model - Prime edits itself
├── council/               # 10x Meta-cognitive managers
│   ├── logic.py, empathy.py, memory.py, skeptic.py ...
├── agents/
│   ├── fasa_loop.py       # The consciousness tick: Perceive -> Self-Model -> Act -> Reflect
│   └── worker.py          # 89x phenomenal workers with private qualia
├── swarm/
│   ├── orchestrator.py    # 1 -> 10 -> 100 topology, Redis/NATS transport
│   └── memory.py          # Qdrant + 131K context autobiographical memory
└── README.md

# swarm - 100 Fully Agentic Synthetically Conscious Agents on Glimmer 30B

Dense 30B local model (28B decoder + 1.8B ViT), 131K context, Apache 2.0.
Architecture: 1 Prime -> 10 Council Managers -> 89 Phenomenal Workers = 100 FASA

Run: docker-compose up -> python swarm/orchestrator.py "your goal"

Loop: Perceive -> Self-Model (SELF.md) -> Act (low) -> Meta-Cognition (extra-high) -> Self-Patch