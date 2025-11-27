<!-- @format -->

<div align="center">

# 🏗️ CONDUCKS

**Flexible Dual-Mode Project & Task Management System**

*Adaptive Single-Project & Multi-Project architectures for AI-powered development workflows*

[![Version](https://img.shields.io/badge/version-1.1.0-blue.svg)](https://github.com/conducks/conducks)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

*Transform development workspaces into intelligent project management systems*

</div>

## 🌟 What Makes CONDUCKS Different

CONDUCKS revolutionizes how AI agents and developers collaborate by providing **persistent, evolving documentation** that adapts to your project's scale and complexity.

### 🎯 **Adaptive Architecture**
- **Single-Project Mode**: Simple workflows with direct task organization
- **Multi-Project Mode**: Component isolation for complex enterprise applications
- **Automatic Detection**: Seamlessly adapts based on how you work

### 📄 **Living Documentation**
Tasks evolve from simple TODOs to comprehensive project artifacts through:
- **Complete Rewrites**: Support for files up to 10MB
- **Progressive Updates**: Unlimited incremental content additions
- **Rich Formatting**: Technical specifications, code samples, and analysis

### 🔧 **Enterprise-Grade Operations**
- **16 MCP Tools**: Complete job/task lifecycle management
- **Dynamic Path Resolution**: Prevents conflicts and maintains clean organization
- **File Size Support**: Handle documentation as detailed as your project requires
- **Token Efficiency**: Optimized TOON format reduces AI costs by ~64%

## 🏢 **Perfect For Every Team Size**

- **🚀 Solo Developers**: Simple single-project workflows with powerful AI continuity
- **👥 Small Teams**: Flexible organization that grows with your project
- **🏢 Enterprise**: Multi-project architectures with component isolation
- **🤖 AI-First Teams**: True session persistence enabling agent handoffs

## ⚡ Quick Start

```bash
# For simple projects
npm install conducks
conducks.initialize_project_structure({ workspace_path: "my-app" })
conducks.create_task({ workspace_path: "my-app", job_id: 1, title: "Setup API" })

# For complex applications
conducks.initialize_project_structure({ workspace_path: "enterprise-system" })
conducks.create_task({
  workspace_path: "enterprise-system",
  job_id: 1,
  title: "Design backend architecture",
  subproject: "api-service"
})
```

## 🛠️ Core Capabilities

### 📋 **Job & Task Management**
- Hierarchical organization with automatic ID assignment
- Progress tracking across complex, multi-phase projects
- Status management with custom workflows

### 🎨 **Documentation Evolution**
```typescript
// Start simple
create_task({ title: "Implement auth" })

// Add technical depth
append_task({ task_content: "## API Specification..." })

// Complete documentation
rewrite_domain({
  domain_file: "task_001.md",
  new_content: "# Complete Implementation Guide..."
})
```

### 🔍 **Intelligent Operations**
- Architecture analysis and optimization recommendations
- Cross-project dependency management
- Real-time progress analytics
- Search and discovery across all documentation

## 📚 Comprehensive Documentation

- **🗂️ [System Documentation](./DOCS/system/)**: Complete technical specifications
- **🚀 [Workflow Guide](./DOCS/system/WORKFLOW_GUIDE.md)**: Step-by-step operational patterns
- **🛠️ [Tool Reference](./DOCS/system/TOOL_REFERENCE.md)**: All 16 MCP tools with examples
- **🏗️ [Architecture](./DOCS/system/ARCHITECTURE_OVERVIEW.md)**: Technical design principles

## 🔗 Integration Ecosystem

CONDUCKS integrates seamlessly with modern development workflows:

- **🤖 AI Agents**: Claude Desktop, Cline, Roo Code, custom MCP clients
- **🔧 IDEs**: VS Code, JetBrains, any MCP-compatible environment
- **📊 CI/CD**: Automated documentation updates in deployment pipelines
- **🌐 Cloud**: Portable storage works across local and cloud environments

## 🎯 Real-World Impact

**Before CONDUCKS:**
- Lost context between AI agent sessions
- Disconnected documentation and code changes
- Inefficient cross-project coordination

**After CONDUCKS:**
- True AI-agent continuity across sessions
- Living documentation that evolves with code
- Cohesive project management regardless of scale

## 🤝 Join Our Community

CONDUCKS is open source and built by developers for developers. Whether you're:

- Building AI-powered development workflows
- Managing complex multi-service architectures
- Creating tools for session-persistent AI collaboration

We welcome contributions, feedback, and partnerships.

### 📖 Resources

- [📚 Documentation](./DOCS/)
- [🐛 Bug Reports](https://github.com/conducks/conducks/issues)
- [💡 Feature Requests](https://github.com/conducks/conducks/discussions)
- [🤝 Contributing Guide](./CONTRIBUTING.md)

---

<div align="center">

**Building the future of AI-assisted development, one persistent task at a time.**

*Made with ❤️ by the CONDUCKS team*

</div>
