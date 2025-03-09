# Function: <code>rproc_stop_subdevices</code>

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
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588232495,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1141",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589107327,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1152",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589106479,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1210",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
void rproc_stop_subdevices(struct rproc * rproc, bool crashed)
```

```json
{
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588993552,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1216",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588993552,
      "name": "rproc_stop_subdevices",
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void rproc_stop_subdevices(struct rproc * rproc, bool crashed)
```

```json
{
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589707632,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1232",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589707632,
      "name": "rproc_stop_subdevices",
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void rproc_stop_subdevices(struct rproc * rproc, bool crashed)
```

```json
{
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591214768,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1228",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/remoteproc/remoteproc_core.c:rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591214768,
      "name": "rproc_stop_subdevices",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 83
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
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592966918,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1121",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593417302,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1122",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071594163254,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1122",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:__rproc_detach",
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501689220,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1141",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3234214608,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1141",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295121152,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1141",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587844191,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1141",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "rproc_stop_subdevices",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588304831,
      "name": "rproc_stop_subdevices",
      "external": false,
      "loc": "drivers/remoteproc/remoteproc_core.c:1141",
      "file": "drivers/remoteproc/remoteproc_core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/remoteproc/remoteproc_core.c:rproc_stop"
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
<summary>Added between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➕</summary>

```c
void rproc_stop_subdevices(struct rproc * rproc, bool crashed)
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
<details>
<summary>Removed between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➖</summary>

```c
void rproc_stop_subdevices(struct rproc * rproc, bool crashed)
```
</details>
</li>
</ul>
