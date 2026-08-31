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