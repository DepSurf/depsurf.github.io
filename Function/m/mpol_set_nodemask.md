# Function: <code>mpol_set_nodemask</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int mpol_set_nodemask(struct mempolicy * pol, const nodemask_t * nodes, struct nodemask_scratch * nsc)
```

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580813632,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:214",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:do_set_mempolicy",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:mpol_shared_policy_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580813632,
      "name": "mpol_set_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int mpol_set_nodemask(struct mempolicy * pol, const nodemask_t * nodes, struct nodemask_scratch * nsc)
```

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580939088,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:213",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580939088,
      "name": "mpol_set_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 207
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
int mpol_set_nodemask(struct mempolicy * pol, const nodemask_t * nodes, struct nodemask_scratch * nsc)
```

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071581007888,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:213",
      "file": "mm/mempolicy.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581007888,
      "name": "mpol_set_nodemask",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 686
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581067707,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:201",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581054096,
      "name": "mpol_set_nodemask.part.19",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 672
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581178843,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:SYSC_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581165232,
      "name": "mpol_set_nodemask.part.21",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581323708,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581308544,
      "name": "mpol_set_nodemask.part.25",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581407868,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581395712,
      "name": "mpol_set_nodemask.part.27",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 678
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581520024,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581507952,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581584584,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581572320,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581796440,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:229",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581778512,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581844344,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:229",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581825760,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 711
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
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581875208,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:229",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581857392,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 709
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582166760,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:221",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582147392,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582623991,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:224",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582602128,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583148343,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:224",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583125184,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583358635,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:224",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583335520,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583594627,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:229",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583571136,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 643
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
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336493022432,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336493009488,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 288
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055286451144,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:do_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055286431632,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 468
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581553320,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581541056,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581494968,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581482704,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581544632,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581532368,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓</summary>

```json
{
  "name": "mpol_set_nodemask",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581609710,
      "name": "mpol_set_nodemask",
      "external": false,
      "loc": "mm/mempolicy.c:203",
      "file": "mm/mempolicy.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ],
      "caller_func": [
        "mm/mempolicy.c:mpol_shared_policy_init",
        "mm/mempolicy.c:kernel_mbind",
        "mm/mempolicy.c:do_set_mempolicy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581597440,
      "name": "mpol_set_nodemask.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 706
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
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int mpol_set_nodemask(struct mempolicy * pol, const nodemask_t * nodes, struct nodemask_scratch * nsc)
```
</details>
</li>
</ul>
