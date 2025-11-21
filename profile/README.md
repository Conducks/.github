# CONDUCKS

**Collaborative Documentation & Knowledge System**

> Intelligent, session-persistent documentation management for AI-powered development workflows

## What is CONDUCKS?

CONDUCKS is an MCP (Model Context Protocol) server that solves the chaos of iterative AI coding. When vibe coding with AI agents, you lose track of changes, fixes, and their ripple effects across sessions. CONDUCKS provides **persistent job and task tracking** that survives session breaks, enabling true continuity in AI-assisted development.

## The Problem We Solve

🔄 **Session Amnesia**: AI agents forget everything when sessions restart  
🤯 **Change Confusion**: You don't know what was changed, fixed, or broken  
🔗 **Lost Context**: Cross-project tasks and dependencies get lost  
📊 **No Traceability**: Can't track progress or understand the bigger picture

## The CONDUCKS Solution

✅ **Persistent Memory**: Jobs and tasks survive across all sessions  
✅ **Hierarchical Organization**: Jobs contain tasks, tasks span projects  
✅ **Smart Continuation**: Agents pick up exactly where they left off  
✅ **Archive System**: Completed jobs move to archive for future reference  
✅ **Cross-Project Tracking**: Handle dependencies between multiple projects  
✅ **Agent Intelligence**: Analyze code, suggest improvements, connect context

## Repositories

### 🔧 [conducks-mcp](./CONDUCKS_SERVER)
The MCP server implementation. Provides tools for job creation, task management, and persistent documentation organization.

**Features:**
- Hierarchical Jobs→Tasks system with numbered IDs
- TOON format for token-efficient storage
- Real-time task status tracking
- Cross-service dependency mapping
- Automatic project structure mirroring

### 📚 [conducks-docs](./DOCS)
Complete documentation, implementation guides, and architecture specifications.

### 🌐 conducks-web *(coming soon)*
Web interface for visualizing jobs, tasks, and project progress.

## Quick Start

```bash
# Clone the MCP server
git clone https://github.com/YOUR_ORG/conducks-mcp.git
cd conducks-mcp

# Install and build
npm install
npm run build

# Run the server
node build/index.js
```

## How It Works

1. **Create Jobs**: High-level goals organized by domain
2. **Add Tasks**: Break jobs into actionable tasks across projects
3. **Track Progress**: Update status as work progresses
4. **Session Continuity**: Agent resumes exactly where it left off
5. **Archive Completion**: Move finished jobs to archive

## Architecture

```
CONDUCKS_SERVER/
├── storage/              # Persistent storage (portable)
│   ├── jobs.toon        # Jobs and tasks database
│   └── <project>/       # Project-specific organization
│       ├── to-do/       # Active tasks
│       └── done-to-do/  # Completed tasks
└── build/               # Compiled MCP server
```

## Use Cases

- **Iterative Development**: Maintain context across multiple coding sessions
- **Cross-Project Work**: Track dependencies between microservices
- **Team Collaboration**: Share structured knowledge about ongoing work
- **Progress Tracking**: Visualize what's done, active, and pending
- **Knowledge Preservation**: Archive decisions and context for future reference

## Integration

Works with any MCP-compatible client:
- ✅ Claude Desktop
- ✅ Cline (VS Code)
- ✅ Roo Code
- ✅ Custom MCP clients

## Why CONDUCKS?

Traditional documentation becomes stale and disconnected. CONDUCKS keeps documentation **alive** by:
- Tracking actual work as it happens
- Connecting tasks to their context
- Preserving intent and decisions
- Enabling true AI-agent continuity

## Contributing

We welcome contributions! Check out individual repositories for specific contribution guidelines.

## License

MIT License - See individual repositories for details.

---

**Built for developers who vibe code with AI and need their agents to remember.**
