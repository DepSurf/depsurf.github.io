# Function: <code>delayed_uprobe_delete</code>

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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580895728,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:323",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580895728,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 62
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:311",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580993248,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 18446744071581005352,
      "name": "delayed_uprobe_delete.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 19
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581047248,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581047248,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581226768,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:314",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581226768,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581269296,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:314",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581269296,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581287952,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:314",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581287952,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581542046,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:314",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_mmap"
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
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581892594,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:308",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_mmap"
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
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582326050,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:310",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_clear_state",
        "kernel/events/uprobes.c:uprobe_mmap"
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
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582526511,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:309",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
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
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071582695423,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:309",
      "file": "kernel/events/uprobes.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/events/uprobes.c:uprobe_mmap"
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492403632,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492403632,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226288660,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226288660,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285667088,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap",
        "kernel/events/uprobes.c:delayed_uprobe_remove"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285667088,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581016096,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581016096,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580962224,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580962224,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007296,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007296,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
```

```json
{
  "name": "delayed_uprobe_delete",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581068688,
      "name": "delayed_uprobe_delete",
      "external": false,
      "loc": "kernel/events/uprobes.c:320",
      "file": "kernel/events/uprobes.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/events/uprobes.c:uprobe_mmap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581068688,
      "name": "delayed_uprobe_delete",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 59
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
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
<details>
<summary>Removed between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➖</summary>

```c
void delayed_uprobe_delete(struct delayed_uprobe * du)
```
</details>
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
void delayed_uprobe_delete(struct delayed_uprobe * du)
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
