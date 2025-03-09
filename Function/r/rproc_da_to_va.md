# Function: <code>rproc_da_to_va</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588230528,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:190",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588230528,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589105344,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:193",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_coredump",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589105344,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589104256,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:192",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104256,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len, bool * is_iomem)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588994768,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:192",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588994768,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 157
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len, bool * is_iomem)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589709172,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:194",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592680799,
      "name": "rproc_da_to_va.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071589709104,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 181
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len, bool * is_iomem)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071591216528,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:194",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594566236,
      "name": "rproc_da_to_va.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071591216448,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len, bool * is_iomem)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592962240,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:193",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596319373,
      "name": "rproc_da_to_va.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071592962160,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len, bool * is_iomem)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593412608,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:193",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596849036,
      "name": "rproc_da_to_va.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071593412528,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline, Transformation ❓</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, size_t len, bool * is_iomem)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071594158320,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:193",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_coredump.c:rproc_copy_segment",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597773747,
      "name": "rproc_da_to_va.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071594158240,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 207
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501686712,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:190",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501686712,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 188
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234212208,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:190",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234212208,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295120192,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:190",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295120192,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 248
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587842224,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:190",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587842224,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```

```json
{
  "name": "rproc_da_to_va",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588302864,
      "name": "rproc_da_to_va",
      "external": true,
      "loc": "drivers/remoteproc/remoteproc_core.c:190",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_trigger_recovery",
        "drivers/remoteproc/remoteproc_debugfs.c:rproc_trace_read",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_find_loaded_rsc_table",
        "drivers/remoteproc/remoteproc_elf_loader.c:rproc_elf_load_segments"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588302864,
      "name": "rproc_da_to_va",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 134
    }
  ]
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ➕</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>int len</code> ➡️ <code>size_t len</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool * is_iomem</code>
</li>
</ul>
</details>
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ➖</summary>

```c
void * rproc_da_to_va(struct rproc * rproc, u64 da, int len)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
