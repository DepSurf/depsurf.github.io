# Function: <code>ftrace_ops_test</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580158528,
      "name": "ftrace_ops_test",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1512",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_control_func",
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580158528,
      "name": "ftrace_ops_test.isra.9",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580193072,
      "name": "ftrace_ops_test",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1481",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580193072,
      "name": "ftrace_ops_test.isra.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "ftrace_ops_test",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580233696,
      "name": "ftrace_ops_test",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1487",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580233696,
      "name": "ftrace_ops_test.isra.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 93
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
  "name": "ftrace_ops_test",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580244336,
      "name": "ftrace_ops_test",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1572",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_entry_test",
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580244336,
      "name": "ftrace_ops_test.isra.23",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "ftrace_ops_test",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580295952,
      "name": "ftrace_ops_test",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1548",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_graph_entry_test",
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580295952,
      "name": "ftrace_ops_test.isra.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
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
  "name": "ftrace_ops_test",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580357104,
      "name": "ftrace_ops_test",
      "external": false,
      "loc": "kernel/trace/ftrace.c:1537",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580357104,
      "name": "ftrace_ops_test.isra.29",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580418976,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1486",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580418976,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580472688,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1483",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580472688,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580520832,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580520832,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580607316,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1477",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580611872,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580597379,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1476",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580602064,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580599680,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1476",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580604784,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580770811,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1477",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580776144,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 99
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580988698,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1471",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:arch_ftrace_ops_list_func",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580994512,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581286202,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1477",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:arch_ftrace_ops_list_func",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581292272,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581381932,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1508",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:arch_ftrace_ops_list_func",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581387376,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581489628,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1507",
      "file": "kernel/trace/ftrace.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/trace/ftrace.c:arch_ftrace_ops_list_func",
        "kernel/trace/ftrace.c:__ftrace_hash_rec_update"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581495392,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 132
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491801824,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_no_ops"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491801824,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225749372,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3225749372,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 148
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284857248,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284857248,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 164
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272113846,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272113846,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 72
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580489632,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580489632,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580436656,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580436656,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580480880,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580480880,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
```

```json
{
  "name": "ftrace_ops_test",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580537120,
      "name": "ftrace_ops_test",
      "external": true,
      "loc": "kernel/trace/ftrace.c:1484",
      "file": "kernel/trace/ftrace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/trace/ftrace.c:ftrace_ops_list_func"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580537120,
      "name": "ftrace_ops_test",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 65
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
int ftrace_ops_test(struct ftrace_ops * ops, long unsigned int ip, void * regs)
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
