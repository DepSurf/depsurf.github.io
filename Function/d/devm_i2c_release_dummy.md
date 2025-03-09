# Function: <code>devm_i2c_release_dummy</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587477328,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:928",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587477328,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587680480,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:933",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587680480,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588548256,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:895",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588548256,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588573808,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:1023",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588573808,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devm_i2c_release_dummy(void * client)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588465868,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:1063",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588457344,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devm_i2c_release_dummy(void * client)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589133980,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:1064",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589125424,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 31
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devm_i2c_release_dummy(void * client)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590583708,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:1066",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590570816,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devm_i2c_release_dummy(void * client)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592241596,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:1060",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592224752,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devm_i2c_release_dummy(void * client)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592666723,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:1104",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592649232,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Selective Inline ❓</summary>

```c
void devm_i2c_release_dummy(void * client)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593412115,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:1112",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/i2c/i2c-core-base.c:devm_i2c_new_dummy_device"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593394384,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 22
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
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336500839256,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:933",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336500839256,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
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
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233356164,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:933",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233356164,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 48
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
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294300848,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:933",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294300848,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
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
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277644618,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:933",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277644618,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 50
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
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587631728,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:933",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587631728,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
void devm_i2c_release_dummy(struct device * dev, void * res)
```

```json
{
  "name": "devm_i2c_release_dummy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587742848,
      "name": "devm_i2c_release_dummy",
      "external": false,
      "loc": "drivers/i2c/i2c-core-base.c:933",
      "file": "drivers/i2c/i2c-core-base.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587742848,
      "name": "devm_i2c_release_dummy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 34
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void devm_i2c_release_dummy(struct device * dev, void * res)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>void * client</code>
</li>
<li>
<b>Param removed. </b>
<code>struct device * dev</code>
</li>
<li>
<b>Param removed. </b>
<code>void * res</code>
</li>
</ul>
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
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1009-aws-amd64</code> ➖</summary>

```c
void devm_i2c_release_dummy(struct device * dev, void * res)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-1010-azure-amd64</code> ➖</summary>

```c
void devm_i2c_release_dummy(struct device * dev, void * res)
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
