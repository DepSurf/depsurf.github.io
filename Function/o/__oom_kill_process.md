# Function: <code>__oom_kill_process</code>

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
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
void __oom_kill_process(struct task_struct * victim)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:846",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580960960,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 334
    },
    {
      "addr": 18446744071580965843,
      "name": "__oom_kill_process.cold.28",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 234
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581057072,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581057072,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 655
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581112768,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581112768,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296496,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:858",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296496,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 911
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:860",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581340560,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 892
    },
    {
      "addr": 18446744071591324824,
      "name": "__oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:859",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581359056,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 865
    },
    {
      "addr": 18446744071591266865,
      "name": "__oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:860",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581606912,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 859
    },
    {
      "addr": 18446744071592190736,
      "name": "__oom_kill_process.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 97
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581966080,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:917",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581966080,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1161
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582402096,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:916",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582402096,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1210
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582608128,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:916",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582608128,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582779504,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:913",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582779504,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1197
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492480312,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492480312,
      "name": "__oom_kill_process",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226354584,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226354584,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 936
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055285765360,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285765360,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1048
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272546370,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272546370,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 794
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581081616,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581081616,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581028800,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581028800,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581072816,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581072816,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 715
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
void __oom_kill_process(struct task_struct * victim, const char * message)
```

```json
{
  "name": "__oom_kill_process",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581134480,
      "name": "__oom_kill_process",
      "external": false,
      "loc": "mm/oom_kill.c:856",
      "file": "mm/oom_kill.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/oom_kill.c:oom_kill_process"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581134480,
      "name": "__oom_kill_process",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 755
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
void __oom_kill_process(struct task_struct * victim)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const char * message</code>
</li>
</ul>
</details>
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
