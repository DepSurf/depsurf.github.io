# Function: <code>vc_handle_mmio</code>

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
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
```

```json
{
  "name": "vc_handle_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579384640,
      "name": "vc_handle_mmio",
      "external": false,
      "loc": "arch/x86/kernel/sev-es.c:924",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:vc_handle_exitcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579384640,
      "name": "vc_handle_mmio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 878
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
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
```

```json
{
  "name": "vc_handle_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579386016,
      "name": "vc_handle_mmio",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1003",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579386016,
      "name": "vc_handle_mmio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
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
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
```

```json
{
  "name": "vc_handle_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579447904,
      "name": "vc_handle_mmio",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:999",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579447904,
      "name": "vc_handle_mmio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1127
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
```

```json
{
  "name": "vc_handle_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579522400,
      "name": "vc_handle_mmio",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1536",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579522400,
      "name": "vc_handle_mmio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 975
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
```

```json
{
  "name": "vc_handle_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_handle_mmio",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1536",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579622656,
      "name": "vc_handle_mmio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1168
    },
    {
      "addr": 18446744071595968170,
      "name": "vc_handle_mmio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
```

```json
{
  "name": "vc_handle_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_handle_mmio",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1493",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579636592,
      "name": "vc_handle_mmio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1195
    },
    {
      "addr": 18446744071596485795,
      "name": "vc_handle_mmio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
```

```json
{
  "name": "vc_handle_mmio",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_handle_mmio",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1522",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_exitcode"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579666384,
      "name": "vc_handle_mmio",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1229
    },
    {
      "addr": 18446744071597382405,
      "name": "vc_handle_mmio.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
enum es_result vc_handle_mmio(struct ghcb * ghcb, struct es_em_ctxt * ctxt)
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
No changes between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
