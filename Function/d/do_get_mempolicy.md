# Function: <code>do_get_mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580815136,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:830",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:compat_SyS_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580815136,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 888
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940528,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:862",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:compat_SyS_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940528,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 915
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581011790,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:864",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_get_mempolicy"
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
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581059278,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:797",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581170302,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:839",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:SYSC_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581314899,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:814",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581398806,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:843",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581510901,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:870",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581575269,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:871",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581785408,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:940",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581785408,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1326
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581830272,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:939",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581830272,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1407
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581860688,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:949",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581860688,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1701
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582152528,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:920",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582152528,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1439
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582607440,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:916",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582607440,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1675
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583130528,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:930",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583130528,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1729
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340720,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:935",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340720,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1769
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
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576880,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:889",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:kernel_get_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576880,
      "name": "do_get_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1786
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336493011996,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:871",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055286439156,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:871",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581544005,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:871",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581485653,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:871",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581535317,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:871",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
  "name": "do_get_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071581600389,
      "name": "do_get_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:871",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:kernel_get_mempolicy"
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ➖</summary>

```c
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
long int do_get_mempolicy(int * policy, nodemask_t * nmask, long unsigned int addr, long unsigned int flags)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
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
