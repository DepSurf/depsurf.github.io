# Function: <code>dyn_event_open</code>

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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580657744,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:169",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580657744,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 61
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580719344,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:169",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580719344,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 63
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580767760,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580767760,
      "name": "dyn_event_open",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580884096,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580884096,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580878512,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580878512,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580882448,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:184",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580882448,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581083568,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:222",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581083568,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 77
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581345216,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:222",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581345216,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581679040,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:224",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581679040,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 85
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581820624,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:224",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581820624,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581942240,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:224",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581942240,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492079256,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492079256,
      "name": "dyn_event_open",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3225979468,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225979468,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 100
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285266688,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285266688,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 148
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580736560,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580736560,
      "name": "dyn_event_open",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580682752,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580682752,
      "name": "dyn_event_open",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580727808,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580727808,
      "name": "dyn_event_open",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
int dyn_event_open(struct inode * inode, struct file * file)
```

```json
{
  "name": "dyn_event_open",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580785760,
      "name": "dyn_event_open",
      "external": false,
      "loc": "kernel/trace/trace_dynevent.c:173",
      "file": "kernel/trace/trace_dynevent.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580785760,
      "name": "dyn_event_open",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 75
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
int dyn_event_open(struct inode * inode, struct file * file)
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
int dyn_event_open(struct inode * inode, struct file * file)
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
