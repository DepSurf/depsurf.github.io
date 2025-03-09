# Function: <code>enter_s2idle_proper</code>

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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587119251,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587418799,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587598991,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587875791,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588081391,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```

```json
{
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588942992,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:136",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588942992,
      "name": "enter_s2idle_proper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 199
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
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```

```json
{
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588955360,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:137",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588955360,
      "name": "enter_s2idle_proper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 227
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588844332,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:137",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589541532,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:137",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```

```json
{
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591031280,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:137",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591031280,
      "name": "enter_s2idle_proper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```

```json
{
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592741856,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:139",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592741856,
      "name": "enter_s2idle_proper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 410
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
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```

```json
{
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596941600,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:140",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596941600,
      "name": "enter_s2idle_proper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```

```json
{
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597869072,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:140",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597869072,
      "name": "enter_s2idle_proper",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 391
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501324888,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233815084,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294868752,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587481487,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588037535,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
  "name": "enter_s2idle_proper",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588153119,
      "name": "enter_s2idle_proper",
      "external": false,
      "loc": "drivers/cpuidle/cpuidle.c:131",
      "file": "drivers/cpuidle/cpuidle.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpuidle/cpuidle.c:cpuidle_enter_s2idle"
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
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
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
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
void enter_s2idle_proper(struct cpuidle_driver * drv, struct cpuidle_device * dev, int index)
```
</details>
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
