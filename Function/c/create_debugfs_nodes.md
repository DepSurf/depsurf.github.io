# Function: <code>create_debugfs_nodes</code>

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
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596702271,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:453",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603032980,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:452",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071603205779,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:452",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605016229,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:452",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605129448,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:482",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605169791,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:483",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
int create_debugfs_nodes()
```

```json
{
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071609436269,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:483",
      "file": "drivers/ras/cec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071609436269,
      "name": "create_debugfs_nodes",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 181
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
int create_debugfs_nodes()
```

```json
{
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071612510913,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:472",
      "file": "drivers/ras/cec.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/ras/cec.c:cec_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071612510913,
      "name": "create_debugfs_nodes",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 181
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614653552,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:481",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615612864,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:481",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071617422441,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:481",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071628177742,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:481",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071619945678,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:481",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071622256990,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:481",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605058446,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:483",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605027238,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:483",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605145994,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:483",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
  "name": "create_debugfs_nodes",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605173985,
      "name": "create_debugfs_nodes",
      "external": false,
      "loc": "drivers/ras/cec.c:483",
      "file": "drivers/ras/cec.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/ras/cec.c:cec_init"
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
int create_debugfs_nodes()
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
int create_debugfs_nodes()
```
</details>
</li>
</ul>
