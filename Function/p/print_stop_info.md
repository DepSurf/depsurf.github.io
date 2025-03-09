# Function: <code>print_stop_info</code>

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
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void print_stop_info(const char * log_lvl, struct task_struct * task)
```

```json
{
  "name": "print_stop_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_stop_info",
      "external": true,
      "loc": "kernel/stop_machine.c:52",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591315621,
      "name": "print_stop_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580429824,
      "name": "print_stop_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 38
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
void print_stop_info(const char * log_lvl, struct task_struct * task)
```

```json
{
  "name": "print_stop_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_stop_info",
      "external": true,
      "loc": "kernel/stop_machine.c:52",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591257861,
      "name": "print_stop_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
    },
    {
      "addr": 18446744071580433888,
      "name": "print_stop_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 33
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
void print_stop_info(const char * log_lvl, struct task_struct * task)
```

```json
{
  "name": "print_stop_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_stop_info",
      "external": true,
      "loc": "kernel/stop_machine.c:52",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592162347,
      "name": "print_stop_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580598624,
      "name": "print_stop_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 85
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
void print_stop_info(const char * log_lvl, struct task_struct * task)
```

```json
{
  "name": "print_stop_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "print_stop_info",
      "external": true,
      "loc": "kernel/stop_machine.c:52",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593935452,
      "name": "print_stop_info.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 28
    },
    {
      "addr": 18446744071580801904,
      "name": "print_stop_info",
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void print_stop_info(const char * log_lvl, struct task_struct * task)
```

```json
{
  "name": "print_stop_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581087232,
      "name": "print_stop_info",
      "external": true,
      "loc": "kernel/stop_machine.c:52",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581087232,
      "name": "print_stop_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void print_stop_info(const char * log_lvl, struct task_struct * task)
```

```json
{
  "name": "print_stop_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581179040,
      "name": "print_stop_info",
      "external": true,
      "loc": "kernel/stop_machine.c:52",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581179040,
      "name": "print_stop_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
void print_stop_info(const char * log_lvl, struct task_struct * task)
```

```json
{
  "name": "print_stop_info",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581284720,
      "name": "print_stop_info",
      "external": true,
      "loc": "kernel/stop_machine.c:52",
      "file": "kernel/stop_machine.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "lib/dump_stack.c:dump_stack_print_info"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581284720,
      "name": "print_stop_info",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 141
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void print_stop_info(const char * log_lvl, struct task_struct * task)
```
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
