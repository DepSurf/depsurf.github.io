# Function: <code>idle_inject_wakeup</code>

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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587773504,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587773504,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 94
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588078400,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588078400,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588284208,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588284208,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589164960,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:85",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589161184,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:86",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589055072,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:86",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589773076,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:86",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591283139,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:86",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593032464,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:86",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593032464,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593484384,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:102",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593484384,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594231632,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:102",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594231632,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 143
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501755688,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501755688,
      "name": "idle_inject_wakeup",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234308020,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234308020,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 120
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295201472,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295201472,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 224
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588221264,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588221264,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```

```json
{
  "name": "idle_inject_wakeup",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588356560,
      "name": "idle_inject_wakeup",
      "external": false,
      "loc": "drivers/powercap/idle_inject.c:83",
      "file": "drivers/powercap/idle_inject.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/powercap/idle_inject.c:idle_inject_start",
        "drivers/powercap/idle_inject.c:idle_inject_timer_fn"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588356560,
      "name": "idle_inject_wakeup",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 98
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```
</details>
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
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```
</details>
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void idle_inject_wakeup(struct idle_inject_device * ii_dev)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-gcp-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-lowlatency-amd64</code> ✅
</li>
</ul>
