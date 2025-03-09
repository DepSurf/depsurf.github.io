# Function: <code>vc_init_em_ctxt</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.8.0-22-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.10.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.13.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.15.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```

```json
{
  "name": "vc_init_em_ctxt",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591657200,
      "name": "vc_init_em_ctxt",
      "external": false,
      "loc": "arch/x86/kernel/sev-es-shared.c:76",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication"
      ],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579380720,
      "name": "vc_init_em_ctxt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 51
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```

```json
{
  "name": "vc_init_em_ctxt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579382640,
      "name": "vc_init_em_ctxt",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:77",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579382640,
      "name": "vc_init_em_ctxt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 313
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```

```json
{
  "name": "vc_init_em_ctxt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579444352,
      "name": "vc_init_em_ctxt",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:77",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579444352,
      "name": "vc_init_em_ctxt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 362
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_init_em_ctxt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617058618,
      "name": "vc_init_em_ctxt",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:174",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_init_em_ctxt",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627704642,
      "name": "vc_init_em_ctxt",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:174",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```

```json
{
  "name": "vc_init_em_ctxt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579627120,
      "name": "vc_init_em_ctxt",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:177",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579627120,
      "name": "vc_init_em_ctxt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```

```json
{
  "name": "vc_init_em_ctxt",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579656496,
      "name": "vc_init_em_ctxt",
      "external": false,
      "loc": "arch/x86/kernel/sev-shared.c:177",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev.c:vc_raw_handle_exception"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579656496,
      "name": "vc_init_em_ctxt",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 386
    }
  ]
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➕</summary>

```c
enum es_result vc_init_em_ctxt(struct es_em_ctxt * ctxt, struct pt_regs * regs, long unsigned int exit_code)
```
</details>
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
