# Function: <code>delayed_uprobe_remove</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580903154,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:331",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580896176,
      "name": "delayed_uprobe_remove.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581000867,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:319",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993536,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581055715,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047536,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581237652,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:322",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_clear_state"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581227792,
      "name": "delayed_uprobe_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581280420,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:322",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_clear_state"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581270032,
      "name": "delayed_uprobe_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581296900,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:322",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_clear_state"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581288496,
      "name": "delayed_uprobe_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581541976,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:322",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_clear_state"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532896,
      "name": "delayed_uprobe_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 179
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581892524,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:316",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_clear_state"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581881440,
      "name": "delayed_uprobe_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582325980,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:318",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_clear_state"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582314032,
      "name": "delayed_uprobe_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 203
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582527346,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:317",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582515152,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582696258,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:317",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582684032,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 226
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492413768,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492404072,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226297468,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226289084,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 128
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
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285667232,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285667232,
      "name": "delayed_uprobe_remove",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581024563,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016384,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580970659,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962512,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581015763,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007584,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_remove",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581077027,
      "name": "delayed_uprobe_remove",
      "external": false,
      "loc": "kernel/events/uprobes.c:328",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:update_ref_ctr"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068976,
      "name": "delayed_uprobe_remove.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 108
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
void delayed_uprobe_remove(struct uprobe * uprobe, struct mm_struct * mm)
```
</details>
</li>
</ul>
