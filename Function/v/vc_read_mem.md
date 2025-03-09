# Function: <code>vc_read_mem</code>

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
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
```

```json
{
  "name": "vc_read_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579381440,
      "name": "vc_read_mem",
      "external": false,
      "loc": "arch/x86/kernel/sev-es.c:344",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:vc_handle_mmio_movs",
        "arch/x86/kernel/sev-es.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579381440,
      "name": "vc_read_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
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
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
```

```json
{
  "name": "vc_read_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383376,
      "name": "vc_read_mem",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:385",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383376,
      "name": "vc_read_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 231
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
```

```json
{
  "name": "vc_read_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_read_mem",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:372",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579445136,
      "name": "vc_read_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 256
    },
    {
      "addr": 18446744071592081028,
      "name": "vc_read_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
```

```json
{
  "name": "vc_read_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_read_mem",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:402",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579516864,
      "name": "vc_read_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071593848352,
      "name": "vc_read_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
```

```json
{
  "name": "vc_read_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_read_mem",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:402",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579615760,
      "name": "vc_read_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 279
    },
    {
      "addr": 18446744071595968018,
      "name": "vc_read_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
```

```json
{
  "name": "vc_read_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_read_mem",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:414",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579628800,
      "name": "vc_read_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071596485635,
      "name": "vc_read_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
```

```json
{
  "name": "vc_read_mem",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_read_mem",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:414",
      "file": "arch/x86/kernel/sev.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev.c:vc_handle_mmio",
        "arch/x86/kernel/sev.c:vc_handle_ioio"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579658320,
      "name": "vc_read_mem",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 283
    },
    {
      "addr": 18446744071597382245,
      "name": "vc_read_mem.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
enum es_result vc_read_mem(struct es_em_ctxt * ctxt, char * src, char * buf, size_t size)
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
