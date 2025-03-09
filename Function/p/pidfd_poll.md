# Function: <code>pidfd_poll</code>

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
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
unsigned int pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461856,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1722",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461856,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579488176,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579488176,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579515968,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1794",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579515968,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 126
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579497360,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1790",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579497360,
      "name": "pidfd_poll",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579501152,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1789",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579501152,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579571824,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1868",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579571824,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 71
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579662736,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1913",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579662736,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579780384,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1935",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579780384,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579827120,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:2083",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579827120,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579865024,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:2080",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579865024,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 79
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336490619512,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336490619512,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3224700648,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3224700648,
      "name": "pidfd_poll",
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
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055283437088,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055283437088,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271378800,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271378800,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 118
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461840,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461840,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579390800,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579390800,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579461760,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579461760,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 122
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
__poll_t pidfd_poll(struct file * file, struct poll_table_struct * pts)
```

```json
{
  "name": "pidfd_poll",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579494160,
      "name": "pidfd_poll",
      "external": false,
      "loc": "kernel/fork.c:1713",
      "file": "kernel/fork.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579494160,
      "name": "pidfd_poll",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
unsigned int pidfd_poll(struct file * file, struct poll_table_struct * pts)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>unsigned int</code> ➡️ <code>__poll_t</code>
</li>
</ul>
</details>
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
