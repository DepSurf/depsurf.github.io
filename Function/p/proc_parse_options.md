# Function: <code>proc_parse_options</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int proc_parse_options(char * options, struct pid_namespace * pid)
```

```json
{
  "name": "proc_parse_options",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581441376,
      "name": "proc_parse_options",
      "external": false,
      "loc": "fs/proc/root.c:51",
      "file": "fs/proc/root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/root.c:proc_mount",
        "fs/proc/root.c:proc_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581441376,
      "name": "proc_parse_options",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 309
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
int proc_parse_options(char * options, struct pid_namespace * pid)
```

```json
{
  "name": "proc_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581625504,
      "name": "proc_parse_options",
      "external": true,
      "loc": "fs/proc/root.c:36",
      "file": "fs/proc/root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_fill_super",
        "fs/proc/root.c:proc_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581625504,
      "name": "proc_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int proc_parse_options(char * options, struct pid_namespace * pid)
```

```json
{
  "name": "proc_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581713792,
      "name": "proc_parse_options",
      "external": true,
      "loc": "fs/proc/root.c:36",
      "file": "fs/proc/root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_fill_super",
        "fs/proc/root.c:proc_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581713792,
      "name": "proc_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 314
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
int proc_parse_options(char * options, struct pid_namespace * pid)
```

```json
{
  "name": "proc_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581767920,
      "name": "proc_parse_options",
      "external": true,
      "loc": "fs/proc/root.c:38",
      "file": "fs/proc/root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_fill_super",
        "fs/proc/root.c:proc_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581767920,
      "name": "proc_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
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
int proc_parse_options(char * options, struct pid_namespace * pid)
```

```json
{
  "name": "proc_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581917568,
      "name": "proc_parse_options",
      "external": true,
      "loc": "fs/proc/root.c:39",
      "file": "fs/proc/root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_fill_super",
        "fs/proc/root.c:proc_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581917568,
      "name": "proc_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 325
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int proc_parse_options(char * options, struct pid_namespace * pid)
```

```json
{
  "name": "proc_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_parse_options",
      "external": true,
      "loc": "fs/proc/root.c:39",
      "file": "fs/proc/root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_fill_super",
        "fs/proc/root.c:proc_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582102468,
      "name": "proc_parse_options.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071582102016,
      "name": "proc_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int proc_parse_options(char * options, struct pid_namespace * pid)
```

```json
{
  "name": "proc_parse_options",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "proc_parse_options",
      "external": true,
      "loc": "fs/proc/root.c:39",
      "file": "fs/proc/root.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/proc/inode.c:proc_fill_super",
        "fs/proc/root.c:proc_remount"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582196820,
      "name": "proc_parse_options.cold.1",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 17
    },
    {
      "addr": 18446744071582196368,
      "name": "proc_parse_options",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 311
    }
  ]
}
```
</details>
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
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
int proc_parse_options(char * options, struct pid_namespace * pid)
```
</details>
</li>
</ul>
