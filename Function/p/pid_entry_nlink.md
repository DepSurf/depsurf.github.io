# Function: <code>pid_entry_nlink</code>

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
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595589575,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:145",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596519461,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:154",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071602846948,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603020434,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:151",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604819128,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604922893,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604958181,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry * entries, unsigned int n)
```

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609260837,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:157",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609260837,
      "name": "pid_entry_nlink",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 52
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
unsigned int pid_entry_nlink(const struct pid_entry * entries, unsigned int n)
```

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612329492,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:157",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612329492,
      "name": "pid_entry_nlink",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 52
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
unsigned int pid_entry_nlink(const struct pid_entry * entries, unsigned int n)
```

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614469843,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:156",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614469843,
      "name": "pid_entry_nlink",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 52
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
unsigned int pid_entry_nlink(const struct pid_entry * entries, unsigned int n)
```

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615415819,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:158",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615415819,
      "name": "pid_entry_nlink",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 52
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
unsigned int pid_entry_nlink(const struct pid_entry * entries, unsigned int n)
```

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617209641,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:157",
      "file": "fs/proc/base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617209641,
      "name": "pid_entry_nlink",
      "section": ".init.text",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071627912421,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:158",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619675493,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:159",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071621981685,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:159",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511000076,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243478996,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055302661844,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936270718896,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
}
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604863641,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604832693,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604940825,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "pid_entry_nlink",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071604962351,
      "name": "pid_entry_nlink",
      "external": false,
      "loc": "fs/proc/base.c:155",
      "file": "fs/proc/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/base.c:set_proc_pid_nlink",
        "fs/proc/base.c:set_proc_pid_nlink"
      ],
      "caller_func": []
    }
  ],
  "symbols": []
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry * entries, unsigned int n)
```
</details>
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
unsigned int pid_entry_nlink(const struct pid_entry * entries, unsigned int n)
```
</details>
</li>
</ul>
