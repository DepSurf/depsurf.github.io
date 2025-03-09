# Function: <code>m_next</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579916448,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:3899",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580017520,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:532",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581121216,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1249",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581428592,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:189",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579916448,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580017520,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581121216,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581428592,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579947376,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4070",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580049984,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:532",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581286960,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1249",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581610544,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:200",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579947376,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580049984,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581286960,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 57
    },
    {
      "addr": 18446744071581610544,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579978720,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4091",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580089488,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:578",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581365616,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1323",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581699088,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579978720,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580089488,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581365616,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071581699088,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579982672,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4136",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580095136,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:579",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581420864,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1265",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581753280,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:204",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579982672,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580095136,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 24
    },
    {
      "addr": 18446744071581420864,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071581753280,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580029152,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4158",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580147152,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:689",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581562480,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1330",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581900416,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:201",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580029152,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580147152,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581562480,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071581900416,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580084736,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4195",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580206960,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:689",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581718624,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1356",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582084832,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:198",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580084736,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580206960,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581718624,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071582084832,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580132288,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4233",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580259216,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:689",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581805824,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1268",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582179760,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:198",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580132288,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580259216,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581805824,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071582179760,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580179632,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4261",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580310224,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581925024,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582343008,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580179632,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580310224,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581925024,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582343008,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580227632,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580359056,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581997424,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582442176,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580227632,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580359056,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581997424,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582442176,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580294256,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4335",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580432304,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582232576,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1310",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582734352,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:165",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580294256,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580432304,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582232576,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071582734352,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580278144,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4566",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580419808,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582280864,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1313",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582806016,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:165",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580278144,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580419808,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582280864,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071582806016,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580282432,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4505",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580424000,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:684",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582307792,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1324",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582834832,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:165",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580282432,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580424000,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582307792,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071582834832,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580434192,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4528",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580587616,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:700",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582627232,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1333",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583167424,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:165",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580434192,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580587616,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582627232,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
    },
    {
      "addr": 18446744071583167424,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580491776,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module/procfs.c:55",
      "file": "kernel/module/procfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580789280,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:705",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583161168,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1374",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583658528,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:166",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580491776,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071580789280,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583161168,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071583658528,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580743440,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module/procfs.c:55",
      "file": "kernel/module/procfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581073520,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:705",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583736912,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1479",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584269440,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:177",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580743440,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581073520,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583736912,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071584269440,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580825776,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module/procfs.c:55",
      "file": "kernel/module/procfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581164256,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:705",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071583953936,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1453",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584499776,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:177",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580825776,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581164256,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071583953936,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    },
    {
      "addr": 18446744071584499776,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580915216,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module/procfs.c:55",
      "file": "kernel/module/procfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581269856,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:708",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584158208,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1463",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071584723488,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:180",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580915216,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 36
    },
    {
      "addr": 18446744071581269856,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 18446744071584158208,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 91
    },
    {
      "addr": 18446744071584723488,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 124
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491468992,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336491620096,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336493514808,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446603336494054808,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491468992,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 18446603336491620096,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 72
    },
    {
      "addr": 18446603336493514808,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 88
    },
    {
      "addr": 18446603336494054808,
      "name": "m_next",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225452168,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3225575072,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227070212,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 3227515376,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225452168,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 40
    },
    {
      "addr": 3225575072,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 3227070212,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    },
    {
      "addr": 3227515376,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 116
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284418480,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055284611808,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287078608,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 13835058055287710576,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284418480,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
    },
    {
      "addr": 13835058055284611808,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 84
    },
    {
      "addr": 13835058055287078608,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    },
    {
      "addr": 13835058055287710576,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271920020,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936272019962,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273184868,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446743936273555220,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271920020,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    },
    {
      "addr": 18446743936272019962,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446743936273184868,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 78
    },
    {
      "addr": 18446743936273555220,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 112
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580196432,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580327856,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581966160,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582410912,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580196432,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580327856,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581966160,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582410912,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580143872,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580275120,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581903728,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582348608,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580143872,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580275120,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581903728,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582348608,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580187904,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580319104,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071581957440,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582401392,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580187904,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580319104,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071581957440,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582401392,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Collision ❓</summary>

```c
void * m_next(struct seq_file * m, void * p, loff_t * pos)
```

```json
{
  "name": "m_next",
  "collision_type": "Static-Static Collision",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580240144,
      "name": "m_next",
      "external": false,
      "loc": "kernel/module.c:4328",
      "file": "kernel/module.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071580374112,
      "name": "m_next",
      "external": false,
      "loc": "kernel/user_namespace.c:683",
      "file": "kernel/user_namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582028960,
      "name": "m_next",
      "external": false,
      "loc": "fs/namespace.c:1278",
      "file": "fs/namespace.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    },
    {
      "addr": 18446744071582480928,
      "name": "m_next",
      "external": false,
      "loc": "fs/proc/task_mmu.c:202",
      "file": "fs/proc/task_mmu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580240144,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 26
    },
    {
      "addr": 18446744071580374112,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    },
    {
      "addr": 18446744071582028960,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446744071582480928,
      "name": "m_next",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
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
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
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
