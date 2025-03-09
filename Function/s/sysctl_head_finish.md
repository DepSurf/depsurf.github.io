# Function: <code>sysctl_head_finish</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void sysctl_head_finish(struct ctl_table_header * head)
```

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581485888,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:312",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581485888,
      "name": "sysctl_head_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void sysctl_head_finish(struct ctl_table_header * head)
```

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581670416,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:312",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581670416,
      "name": "sysctl_head_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
void sysctl_head_finish(struct ctl_table_header * head)
```

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581758624,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:312",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581758624,
      "name": "sysctl_head_finish",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 65
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
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581813705,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:343",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581812736,
      "name": "sysctl_head_finish.part.22",
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581963257,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:344",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581962288,
      "name": "sysctl_head_finish.part.22",
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582146485,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:344",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582145520,
      "name": "sysctl_head_finish.part.27",
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582241125,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:344",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582240080,
      "name": "sysctl_head_finish.part.27",
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582405730,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582404496,
      "name": "sysctl_head_finish.part.0",
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
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582504690,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582503456,
      "name": "sysctl_head_finish.part.0",
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582807302,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:317",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582806288,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582881014,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:318",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582879968,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582909453,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:313",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582908752,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583243673,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:313",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583242976,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 67
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583744479,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:338",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584358415,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:331",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
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
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584588143,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:325",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
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
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584819831,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:327",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
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
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336494130168,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336494128496,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3227580412,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3227578760,
      "name": "sysctl_head_finish.part.0",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055287808712,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055287806240,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 204
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936273611410,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936273610164,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 138
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582473426,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582472192,
      "name": "sysctl_head_finish.part.0",
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
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582410658,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582409424,
      "name": "sysctl_head_finish.part.0",
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
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582463906,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582462672,
      "name": "sysctl_head_finish.part.0",
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
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "sysctl_head_finish",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582545858,
      "name": "sysctl_head_finish",
      "external": false,
      "loc": "fs/proc/proc_sysctl.c:349",
      "file": "fs/proc/proc_sysctl.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ],
      "caller_func": [
        "fs/proc/proc_sysctl.c:proc_sys_getattr",
        "fs/proc/proc_sysctl.c:proc_sys_permission",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_readdir",
        "fs/proc/proc_sysctl.c:proc_sys_poll",
        "fs/proc/proc_sysctl.c:proc_sys_open",
        "fs/proc/proc_sysctl.c:proc_sys_call_handler",
        "fs/proc/proc_sysctl.c:proc_sys_lookup",
        "fs/proc/proc_sysctl.c:proc_sys_lookup"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582544816,
      "name": "sysctl_head_finish.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 55
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
void sysctl_head_finish(struct ctl_table_header * head)
```
</details>
</li>
</ul>
