# Function: <code>do_set_mempolicy</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580814704,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:753",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:compat_SyS_set_mempolicy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:numa_default_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580814704,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580940096,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:785",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:compat_SyS_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580940096,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581010832,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:787",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:SYSC_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581010832,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 322
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581058352,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:721",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:SYSC_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581058352,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581169376,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:763",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:SYSC_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581169376,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 290
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581313888,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:738",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581313888,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581397792,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:764",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581397792,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 298
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581509888,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:791",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581509888,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581574256,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:792",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581574256,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581784576,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:862",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581784576,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 316
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581829424,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:862",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581829424,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 327
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581859776,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:862",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581859776,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 403
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582151936,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:843",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582151936,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 347
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582606784,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:842",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582606784,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 360
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583129312,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:854",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583129312,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 359
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583340000,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:859",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583340000,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 358
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583576112,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:813",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583576112,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 409
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336493010592,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:792",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493010592,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 352
    }
  ]
}
```
</details>
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055286437728,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:792",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286437728,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 428
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581542992,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:792",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581542992,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581484640,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:792",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581484640,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581534304,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:792",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581534304,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 295
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
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```

```json
{
  "name": "do_set_mempolicy",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581599376,
      "name": "do_set_mempolicy",
      "external": false,
      "loc": "mm/mempolicy.c:792",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:numa_default_policy",
        "mm/mempolicy.c:numa_policy_init",
        "mm/mempolicy.c:kernel_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581599376,
      "name": "do_set_mempolicy",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 291
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
long int do_set_mempolicy(short unsigned int mode, short unsigned int flags, nodemask_t * nodes)
```
</details>
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
