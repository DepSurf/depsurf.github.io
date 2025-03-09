# Function: <code>s2idle_enter</code>

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
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579765597,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:77",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579800840,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:78",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579847464,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:84",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579880954,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579931238,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
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
void s2idle_enter()
```

```json
{
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579974496,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579974496,
      "name": "s2idle_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 437
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
void s2idle_enter()
```

```json
{
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579961392,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/power/suspend.c:suspend_enter"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579961392,
      "name": "s2idle_enter",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 392
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579964114,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580093739,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580230949,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580424111,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:90",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580493714,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:90",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071580553602,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:90",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336491140644,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:s2idle_loop"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3225138776,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055284035448,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579838826,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_devices_and_enter"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579891510,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
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
  "name": "s2idle_enter",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579937350,
      "name": "s2idle_enter",
      "external": false,
      "loc": "kernel/power/suspend.c:88",
      "file": "kernel/power/suspend.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/power/suspend.c:suspend_enter"
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
void s2idle_enter()
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void s2idle_enter()
```
</details>
</li>
</ul>
