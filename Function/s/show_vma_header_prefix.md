# Function: <code>show_vma_header_prefix</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581902200,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582084448,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:276",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582084448,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582178992,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:275",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582178992,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582342224,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582342224,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582441392,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582441392,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582735152,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582735152,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582806816,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806816,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582835632,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582835632,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583168224,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:250",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583168224,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583659408,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:251",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583659408,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584265664,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:254",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584265664,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584495968,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:254",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584495968,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584719344,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:242",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584719344,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 342
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494053976,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494053976,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 340
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227514636,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227514636,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 328
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287709472,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287709472,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 432
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273554572,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273554572,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    }
  ]
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582410128,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582410128,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582347824,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582347824,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582400608,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582400608,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
```

```json
{
  "name": "show_vma_header_prefix",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582480144,
      "name": "show_vma_header_prefix",
      "external": false,
      "loc": "fs/proc/task_mmu.c:279",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_smaps_rollup",
        "fs/proc/task_mmu.c:show_map_vma",
        "fs/proc/task_mmu.c:show_map_vma"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582480144,
      "name": "show_vma_header_prefix",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 321
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
void show_vma_header_prefix(struct seq_file * m, long unsigned int start, long unsigned int end, vm_flags_t flags, long long unsigned int pgoff, dev_t dev, long unsigned int ino)
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
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
