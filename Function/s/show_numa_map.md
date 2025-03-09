# Function: <code>show_numa_map</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int show_numa_map(struct seq_file * m, void * v, int is_pid)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581432544,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1497",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_pid_numa_map",
        "fs/proc/task_mmu.c:show_tid_numa_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581432544,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
int show_numa_map(struct seq_file * m, void * v, int is_pid)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581613632,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1634",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_tid_numa_map",
        "fs/proc/task_mmu.c:show_pid_numa_map"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581613632,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1040
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581702432,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1628",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581702432,
      "name": "show_numa_map.isra.32",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1018
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581756288,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1640",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581756288,
      "name": "show_numa_map.isra.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581902592,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1736",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581902592,
      "name": "show_numa_map.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582088160,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1734",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582088160,
      "name": "show_numa_map.isra.35",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582181824,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1740",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582181824,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1004
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582344240,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1807",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582344240,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1008
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582443184,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1819",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582443184,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582737120,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1793",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582737120,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582808160,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1863",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582808160,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 900
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837712,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1861",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837712,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 867
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583170416,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1888",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583170416,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 881
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583661776,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1909",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583661776,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 898
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584267328,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1940",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584267328,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 902
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584497600,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1947",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584497600,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 964
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584722464,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:2698",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584722464,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1000
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494056080,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1819",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494056080,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 928
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287712016,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1819",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287712016,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1288
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582411920,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1819",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582411920,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582349616,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1819",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582349616,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582402400,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1819",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582402400,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
int show_numa_map(struct seq_file * m, void * v)
```

```json
{
  "name": "show_numa_map",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582482816,
      "name": "show_numa_map",
      "external": false,
      "loc": "fs/proc/task_mmu.c:1819",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582482816,
      "name": "show_numa_map",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 918
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
int show_numa_map(struct seq_file * m, void * v, int is_pid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int show_numa_map(struct seq_file * m, void * v)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
int show_numa_map(struct seq_file * m, void * v)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
int show_numa_map(struct seq_file * m, void * v)
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
