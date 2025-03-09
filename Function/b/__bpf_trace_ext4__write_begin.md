# Function: <code>__bpf_trace_ext4__write_begin</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582504064,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:273",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582504064,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582604272,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582604272,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582776192,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582776192,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582879312,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879312,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583191856,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:314",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583191856,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583288544,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:325",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583288544,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583312784,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:325",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583312784,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583655984,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:325",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583655984,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584223664,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:336",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584223664,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584865136,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:338",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584865136,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585089776,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:352",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585089776,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585321680,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:352",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585321680,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 25
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494531648,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494531648,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3227993832,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3227993832,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 64
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055288340736,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055288340736,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582848048,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582848048,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582785200,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582785200,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582836928,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582836928,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
```

```json
{
  "name": "__bpf_trace_ext4__write_begin",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582923536,
      "name": "__bpf_trace_ext4__write_begin",
      "external": false,
      "loc": "include/trace/events/ext4.h:294",
      "file": "fs/ext4/super.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582923536,
      "name": "__bpf_trace_ext4__write_begin",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 16
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
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
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param removed. </b>
<code>unsigned int flags</code>
</li>
</ul>
</details>
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
void __bpf_trace_ext4__write_begin(void * __data, struct inode * inode, loff_t pos, unsigned int len, unsigned int flags)
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
