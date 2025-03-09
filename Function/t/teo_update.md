# Function: <code>teo_update</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587885187,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:119",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588091377,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588952128,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588952128,
      "name": "teo_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588964384,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588964384,
      "name": "teo_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 318
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
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588853895,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589553360,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:160",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589553360,
      "name": "teo_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 806
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591046992,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:160",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591046992,
      "name": "teo_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592758976,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:160",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592758976,
      "name": "teo_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 829
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593194336,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:227",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593194336,
      "name": "teo_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 982
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593948192,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:228",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/governors/teo.c:teo_select"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593948192,
      "name": "teo_update",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1129
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501338296,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233827652,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294885312,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587712947,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587491457,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "teo_update",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588163329,
      "name": "teo_update",
      "external": false,
      "loc": "drivers/cpuidle/governors/teo.c:117",
      "file": "drivers/cpuidle/governors/teo.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/governors/teo.c:teo_select"
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
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
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
void teo_update(struct cpuidle_driver * drv, struct cpuidle_device * dev)
```
</details>
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
