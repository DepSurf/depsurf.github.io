# Function: <code>bpf_trace_run8</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580568064,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1140",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580568064,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580625616,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1185",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580625616,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 106
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580685904,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1354",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580685904,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580732928,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580732928,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580845968,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1872",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580845968,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580843296,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2128",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580843296,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 191
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580846912,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1824",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580846912,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 184
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581046704,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1908",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581046704,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 180
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295456,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2089",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295456,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 205
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581628576,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2312",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "mm/khugepaged.c:__bpf_trace_mm_khugepaged_collapse_file",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581628576,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581768496,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2321",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "mm/khugepaged.c:__bpf_trace_mm_khugepaged_collapse_file",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581768496,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581886624,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:2426",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/rmap.c:__bpf_trace_mm_migrate_pages",
        "mm/khugepaged.c:__bpf_trace_mm_khugepaged_collapse_file",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "block/blk-iocost.c:__bpf_trace_iocost_iocg_forgive_debt",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply",
        "drivers/thermal/gov_power_allocator.c:__bpf_trace_thermal_power_allocator"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581886624,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 246
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492048976,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492048976,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 196
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225941020,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225941020,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 316
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285211520,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285211520,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 272
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580701728,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580701728,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580647936,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580647936,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580692976,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580692976,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 186
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```

```json
{
  "name": "bpf_trace_run8",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580755616,
      "name": "bpf_trace_run8",
      "external": true,
      "loc": "kernel/trace/bpf_trace.c:1378",
      "file": "kernel/trace/bpf_trace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:__bpf_trace_mm_vmscan_inactive_list_is_low",
        "mm/vmscan.c:__bpf_trace_mm_vmscan_lru_isolate",
        "fs/jbd2/journal.c:__bpf_trace_jbd2_handle_stats",
        "drivers/i2c/i2c-core-smbus.c:__bpf_trace_smbus_reply"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580755616,
      "name": "bpf_trace_run8",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 219
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
void bpf_trace_run8(struct bpf_prog * prog, u64 arg0, u64 arg1, u64 arg2, u64 arg3, u64 arg4, u64 arg5, u64 arg6, u64 arg7)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
