```
  ███╗   ██╗███████╗██╗  ██╗██╗   ██╗███████╗
  ████╗  ██║██╔════╝╚██╗██╔╝██║   ██║██╔════╝
  ██╔██╗ ██║█████╗   ╚███╔╝ ██║   ██║███████╗
  ██║╚██╗██║██╔══╝   ██╔██╗ ██║   ██║╚════██║
  ██║ ╚████║███████╗██╔╝ ██╗╚██████╔╝███████║
  ╚═╝  ╚═══╝╚══════╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝
```

```
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
▓                                                 ▓
▓    performance is a feature, not a goal.        ▓
▓    memory layout matters.                       ▓
▓    streaming > materialization.                 ▓
▓                                                 ▓
▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓
```

</div>

---

## `$ whoami`

Systems engineer. Rust-first, zero-copy by default.  
I build infrastructure that doesn't apologize for being fast.

- Networking, binary parsing, memory layout — this is where I live
- Data-oriented design over clever abstractions
- Compile-time guarantees over runtime surprises
- **Predictable systems > magic systems**

---

## `$ ls active_projects/`

<table>
<tr>
<td width="50%">

### 🛡️ RpcShield
> High-performance RPC proxy for blockchain infrastructure

- Multi-tenant architecture
- Strict billing enforcement modes
- Designed for reliability under adversarial load
- Built to scale without leaking abstractions

</td>
<td width="50%">

### ⛓️ blockchain-zc-parser
> Zero-copy Bitcoin block parser

- **Allocation-free** streaming parser
- Iterates `blkNNNNN.dat` without materialization
- `no_std` friendly — runs anywhere
- Maximum throughput from raw disk to logic

</td>
</tr>
</table>

---

## `$ cat stack.txt`

```rust
struct Stack {
    primary:   &'static str,    // "Rust"
    secondary: [&'static str],  // ["C++23", "Swift", "Python"]
    focus:     [&'static str],  // ["Networking", "Binary parsing", "Memory layout"]
    arch:      [&'static str],  // ["Data-oriented design", "Streaming pipelines"]
    tools:     [&'static str],  // ["Tokio", "Criterion", "CMake", "LLVM"]
}
```

---

## `$ specialization --list`

```
✓  High-throughput services           ✓  Zero-copy parsers
✓  Low-latency networking             ✓  Multi-tenant infra design
✓  Resource-aware architecture        ✓  no_std / embedded-friendly code
```

---

## `$ cat philosophy.rs`

```rust
fn build() -> System {
    System::new()
        .with_principle("Performance is a feature")
        .with_principle("Memory layout matters")
        .prefer(Pipeline::Streaming, Pipeline::Materialized)
        .prefer(Guarantee::CompileTime, Guarantee::Runtime)
        .avoid(Abstraction::Clever)
        .target(Behavior::Predictable)
}
```

---

## `$ top`

<div align="center">

![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)
![C++](https://img.shields.io/badge/C++23-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![LLVM](https://img.shields.io/badge/LLVM-262D3A?style=for-the-badge&logo=llvm&logoColor=white)
![Tokio](https://img.shields.io/badge/Tokio-000000?style=for-the-badge&logo=rust&logoColor=orange)
![Bitcoin](https://img.shields.io/badge/Bitcoin-F7931A?style=for-the-badge&logo=bitcoin&logoColor=white)

</div>

---

## `$ uptime`

```
STATUS   :: building scalable systems
MEMORY   :: predictable
LATENCY  :: minimized
SAFETY   :: enforced by the compiler
PROCESS  :: still running
```

---

<div align="center">

```
// zero warnings. zero allocations. zero compromises.
```

*Open to infra and performance-heavy projects · Rust · Blockchain · Systems design*

</div>
