# Function: <code>vc_handle_exitcode</code>

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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
```

```json
{
  "name": "vc_handle_exitcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_handle_exitcode",
      "external": false,
      "loc": "arch/x86/kernel/sev-es.c:1156",
      "file": "arch/x86/kernel/sev-es.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "arch/x86/kernel/sev-es.c:handle_vc_boot_ghcb",
        "arch/x86/kernel/sev-es.c:safe_stack_exc_vmm_communication"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579385520,
      "name": "vc_handle_exitcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 894
    },
    {
      "addr": 18446744071591265428,
      "name": "vc_handle_exitcode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
```

```json
{
  "name": "vc_handle_exitcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_handle_exitcode",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1227",
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
      "addr": 18446744071579387152,
      "name": "vc_handle_exitcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1530
    },
    {
      "addr": 18446744071591207612,
      "name": "vc_handle_exitcode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
```

```json
{
  "name": "vc_handle_exitcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_handle_exitcode",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1223",
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
      "addr": 18446744071579449040,
      "name": "vc_handle_exitcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1530
    },
    {
      "addr": 18446744071592081151,
      "name": "vc_handle_exitcode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
```

```json
{
  "name": "vc_handle_exitcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "vc_handle_exitcode",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1756",
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
      "addr": 18446744071579523376,
      "name": "vc_handle_exitcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1631
    },
    {
      "addr": 18446744071593848616,
      "name": "vc_handle_exitcode.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
```

```json
{
  "name": "vc_handle_exitcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579623840,
      "name": "vc_handle_exitcode",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1756",
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
      "addr": 18446744071579623840,
      "name": "vc_handle_exitcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1309
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
```

```json
{
  "name": "vc_handle_exitcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579637808,
      "name": "vc_handle_exitcode",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1713",
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
      "addr": 18446744071579637808,
      "name": "vc_handle_exitcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1280
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
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
```

```json
{
  "name": "vc_handle_exitcode",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579667632,
      "name": "vc_handle_exitcode",
      "external": false,
      "loc": "arch/x86/kernel/sev.c:1751",
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
      "addr": 18446744071579667632,
      "name": "vc_handle_exitcode",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1337
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
enum es_result vc_handle_exitcode(struct es_em_ctxt * ctxt, struct ghcb * ghcb, long unsigned int exit_code)
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
