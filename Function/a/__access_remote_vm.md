# Function: <code>__access_remote_vm</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580662048,
      "name": "__access_remote_vm",
      "external": false,
      "loc": "mm/memory.c:3659",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_remote_vm",
        "mm/memory.c:access_process_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580662048,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 716
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, int write)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580771776,
      "name": "__access_remote_vm",
      "external": false,
      "loc": "mm/memory.c:3854",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580771776,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 795
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580865792,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:3932",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580865792,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 798
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580910848,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4222",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580910848,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 727
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581009600,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4400",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581009600,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 786
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581143248,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4448",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581143248,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581223072,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4238",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581223072,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 799
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581296736,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4289",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581296736,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581355504,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581355504,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581553088,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4679",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581553088,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int __access_remote_vm(struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581597744,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4906",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597744,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 894
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
int __access_remote_vm(struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581620592,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4973",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581620592,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 895
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
int __access_remote_vm(struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581888096,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:5119",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581888096,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 796
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
int __access_remote_vm(struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582285808,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:5426",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582285808,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1010
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
int __access_remote_vm(struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582778512,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:5506",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778512,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 988
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
int __access_remote_vm(struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582994816,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:5697",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582994816,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 1127
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
int __access_remote_vm(struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583127472,
      "name": "__access_remote_vm",
      "external": false,
      "loc": "mm/memory.c:5923",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583127472,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336492759280,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492759280,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 468
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3226583032,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226583032,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 460
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286123520,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286123520,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 932
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936272740200,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272740200,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 424
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581324352,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581324352,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581268112,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581268112,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581315552,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581315552,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 814
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
int __access_remote_vm(struct task_struct * tsk, struct mm_struct * mm, long unsigned int addr, void * buf, int len, unsigned int gup_flags)
```

```json
{
  "name": "__access_remote_vm",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581379504,
      "name": "__access_remote_vm",
      "external": true,
      "loc": "mm/memory.c:4314",
      "file": "mm/memory.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/ptrace.c:ptrace_access_vm",
        "mm/memory.c:access_process_vm",
        "mm/memory.c:access_remote_vm"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581379504,
      "name": "__access_remote_vm",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 825
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
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>unsigned int gup_flags</code>
</li>
<li>
<b>Param removed. </b>
<code>int write</code>
</li>
</ul>
</details>
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
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>struct task_struct * tsk</code>
</li>
<li>
<b>Param reordered. </b>
<code>tsk, mm, addr, buf, len, gup_flags</code> ➡️ <code>mm, addr, buf, len, gup_flags</code>
</li>
</ul>
</details>
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
