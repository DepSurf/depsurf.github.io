# Function: <code>setup_boot_config</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609003430,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:395",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609003430,
      "name": "setup_boot_config.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 594
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
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612067969,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:407",
      "file": "init/main.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612067969,
      "name": "setup_boot_config.constprop.0",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 504
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
void setup_boot_config()
```

```json
{
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071614205096,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:408",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071614205096,
      "name": "setup_boot_config",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 622
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
void setup_boot_config()
```

```json
{
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071615124181,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:407",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071615124181,
      "name": "setup_boot_config",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 659
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
void setup_boot_config()
```

```json
{
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071616885956,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:411",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071616885956,
      "name": "setup_boot_config",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 638
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
void setup_boot_config()
```

```json
{
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071627475776,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:414",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071627475776,
      "name": "setup_boot_config",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 695
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
void setup_boot_config()
```

```json
{
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619219488,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:404",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619219488,
      "name": "setup_boot_config",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 752
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
void setup_boot_config()
```

```json
{
  "name": "setup_boot_config",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071621509184,
      "name": "setup_boot_config",
      "external": false,
      "loc": "init/main.c:404",
      "file": "init/main.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "init/main.c:start_kernel"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071621509184,
      "name": "setup_boot_config",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 752
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void setup_boot_config()
```
</details>
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
