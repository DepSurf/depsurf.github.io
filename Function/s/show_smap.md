# Function: <code>show_smap</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int show_smap(struct seq_file * m, void * v, int is_pid)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581431920,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:654",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_pid_smap",
        "fs/proc/task_mmu.c:show_tid_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581431920,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 549
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
int show_smap(struct seq_file * m, void * v, int is_pid)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581621360,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:729",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/task_mmu.c:show_tid_smap",
        "fs/proc/task_mmu.c:show_pid_smap"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581621360,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
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
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581709760,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:722",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581709760,
      "name": "show_smap.isra.33",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581764032,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:723",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581764032,
      "name": "show_smap.isra.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 631
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
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581913360,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:737",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581913360,
      "name": "show_smap.isra.29",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 904
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
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582086800,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:739",
      "file": "fs/proc/task_mmu.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582086800,
      "name": "show_smap.isra.30",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1340
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582182832,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:784",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582182832,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582345248,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:820",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582345248,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582444256,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582444256,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582736512,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:804",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582736512,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582809264,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:816",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582809264,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582837104,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:816",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582837104,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 446
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583169744,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:832",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583169744,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 512
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583661072,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:848",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583661072,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 532
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584268480,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:860",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584268480,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584498816,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:856",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584498816,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 548
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584721616,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:852",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584721616,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336494057216,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494057216,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 496
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227516372,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227516372,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 488
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055287714384,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287714384,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 564
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936273556912,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273556912,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 414
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582412992,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582412992,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582350688,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582350688,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582403472,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582403472,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int show_smap(struct seq_file * m, void * v)
```

```json
{
  "name": "show_smap",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582483968,
      "name": "show_smap",
      "external": false,
      "loc": "fs/proc/task_mmu.c:828",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582483968,
      "name": "show_smap",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 460
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
int show_smap(struct seq_file * m, void * v, int is_pid)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➕</summary>

```c
int show_smap(struct seq_file * m, void * v)
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
