# Function: <code>uprobe_register_refctr</code>

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
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580901872,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1163",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580901872,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580999568,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1151",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580999568,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581054400,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054400,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581236608,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1202",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581236608,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581279296,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1202",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581279296,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581295520,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1200",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581295520,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581540448,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1201",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581540448,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581890736,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1196",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581890736,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582323744,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1199",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582323744,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582525056,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1196",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582525056,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582693984,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1196",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/bpf_trace.c:bpf_uprobe_multi_link_attach",
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582693984,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492412208,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492412208,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226295960,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226295960,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 52
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285678048,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285678048,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 20
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581023248,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581023248,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580969344,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580969344,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581014448,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581014448,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```

```json
{
  "name": "uprobe_register_refctr",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581075712,
      "name": "uprobe_register_refctr",
      "external": true,
      "loc": "kernel/events/uprobes.c:1203",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/trace_uprobe.c:probe_event_enable"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581075712,
      "name": "uprobe_register_refctr",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
```
</details>
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
int uprobe_register_refctr(struct inode * inode, loff_t offset, loff_t ref_ctr_offset, struct uprobe_consumer * uc)
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
