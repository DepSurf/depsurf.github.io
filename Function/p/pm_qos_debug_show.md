# Function: <code>pm_qos_debug_show</code>

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
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579836656,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:187",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579836656,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:188",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579870672,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071579873757,
      "name": "pm_qos_debug_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579919280,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071579923210,
      "name": "pm_qos_debug_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336491126488,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336491126488,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
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
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3225124352,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3225124352,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 500
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
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055284015648,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055284015648,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 784
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
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936271697724,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936271697724,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579891392,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071579895322,
      "name": "pm_qos_debug_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579826352,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071579830282,
      "name": "pm_qos_debug_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579879552,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071579883482,
      "name": "pm_qos_debug_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```

```json
{
  "name": "pm_qos_debug_show",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "pm_qos_debug_show",
      "external": false,
      "loc": "kernel/power/qos.c:140",
      "file": "kernel/power/qos.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579925168,
      "name": "pm_qos_debug_show",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
    },
    {
      "addr": 18446744071579929242,
      "name": "pm_qos_debug_show.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 58
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
int pm_qos_debug_show(struct seq_file * s, void * unused)
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
int pm_qos_debug_show(struct seq_file * s, void * unused)
```
</details>
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
