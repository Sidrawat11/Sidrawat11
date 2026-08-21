# Parth Rawat

I build things to find out how they work.

Professionally that means business rule engines for regulated government identity systems, thousands of statutory rules that have to interact without contradicting each other, where getting it wrong means someone's licence is wrong. C#/.NET, Angular, SQL Server. Two years of it and I still find the edge cases interesting.

Outside of that I go one abstraction layer down for fun. A manhwa upscaler because I got tired of pixelated panels. A VPN in Rust because I wanted to know what a packet actually is.

### Things I've built

**[Encrypted Network Tunnel](https://github.com/Sidrawat11/tether)** · Rust · *repo coming, still learning*
Two machines, one encrypted pipe, no third party in between. Built from the TUN device up — packet capture, IP header parsing by hand, UDP encapsulation, Noise protocol handshake. Targeting Linux and Windows. I'm learning the language by writing it, so it goes up when it does something worth showing.

**[ManwhaHDFyer](https://github.com/Sidrawat11/manwha-hdfyer)** · Python, PyTorch, CUDA
I read a lot of manhwa and the scans are rough. So: GPU-accelerated upscaling with FP16 inference, custom fault-tolerant chunking for the absurd aspect ratios manhwa comes in, and streaming ZIP output that killed 580 MB of temp files per batch.

**[MCP Workflow Toolkit](https://github.com/Sidrawat11/mcp-workflow-toolkit)** · Python, MCP SDK
Starting a new project took five manual steps and I do it often enough to resent it. Four domain-separated MCP servers: filesystem, git, Notion, editor; collapse the whole thing into one sentence. Also involved chasing down a stdio pipe-inheritance bug in Windows subprocess spawning, which was its own adventure.

### Tools

Ship with: C#/.NET 8, Angular, TypeScript, SQL Server (T-SQL), Azure DevOps
Play with: Rust, Python, PyTorch, CUDA, Linux

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/prawat7) · [Email](mailto:paarth.srawat@gmail.com)
