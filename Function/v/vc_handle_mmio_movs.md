# Function: <code>vc_handle_mmio_movs</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_handle_mmio_movs(struct es_em_ctxt * ctxt, unsigned int bytes)
```

```json
{
  "name": "vc_handle_mmio_movs",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383104,
      "name": "vc_handle_mmio_movs",
      "external": false,
      "loc": "arch/x86/kernel/sev-es.c:876",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:vc_handle_mmio",
        "arch/x86/kernel/sev-es.c:vc_handle_mmio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383104,
      "name": "vc_handle_mmio_movs",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 310
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_handle_mmio_movs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579386559,
      "name": "vc_handle_mmio_movs",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:955",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_mmio"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_handle_mmio_movs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579448447,
      "name": "vc_handle_mmio_movs",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:951",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_mmio"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_handle_mmio_movs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579522736,
      "name": "vc_handle_mmio_movs",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1488",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_mmio"
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
  "name": "vc_handle_mmio_movs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579622976,
      "name": "vc_handle_mmio_movs",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1488",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_mmio"
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_handle_mmio_movs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579637083,
      "name": "vc_handle_mmio_movs",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1445",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_mmio"
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "vc_handle_mmio_movs",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579666753,
      "name": "vc_handle_mmio_movs",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1474",
      "file": "arch/x86/kernel/sev.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "arch/x86/kernel/sev.c:vc_handle_mmio"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
enum es_result vc_handle_mmio_movs(struct es_em_ctxt * ctxt, unsigned int bytes)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
enum es_result vc_handle_mmio_movs(struct es_em_ctxt * ctxt, unsigned int bytes)
```
</details>
</li>
</ul>
