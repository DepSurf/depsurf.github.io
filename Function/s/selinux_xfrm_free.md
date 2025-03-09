# Function: <code>selinux_xfrm_free</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void selinux_xfrm_free(struct xfrm_sec_ctx * ctx)
```

```json
{
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582370944,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:125",
      "file": "security/selinux/xfrm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582370944,
      "name": "selinux_xfrm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void selinux_xfrm_free(struct xfrm_sec_ctx * ctx)
```

```json
{
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582592064,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:125",
      "file": "security/selinux/xfrm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582592064,
      "name": "selinux_xfrm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
void selinux_xfrm_free(struct xfrm_sec_ctx * ctx)
```

```json
{
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582685280,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:125",
      "file": "security/selinux/xfrm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582685280,
      "name": "selinux_xfrm_free",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 29
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582779148,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:125",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582778384,
      "name": "selinux_xfrm_free.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582935212,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:125",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582934448,
      "name": "selinux_xfrm_free.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583135212,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:127",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583134416,
      "name": "selinux_xfrm_free.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583251212,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:127",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583250272,
      "name": "selinux_xfrm_free.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583438236,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583437456,
      "name": "selinux_xfrm_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583544140,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583543360,
      "name": "selinux_xfrm_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071583893676,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584013756,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584041772,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071584412940,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585040348,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585759212,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585989836,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:123",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071586237164,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:123",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336495315980,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3228693904,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228692896,
      "name": "selinux_xfrm_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 60
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓</summary>

```json
{
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055289306068,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936274532530,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
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
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583512876,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583512096,
      "name": "selinux_xfrm_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583449932,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583449152,
      "name": "selinux_xfrm_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583496652,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583495872,
      "name": "selinux_xfrm_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
  "name": "selinux_xfrm_free",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071583593020,
      "name": "selinux_xfrm_free",
      "external": false,
      "loc": "security/selinux/xfrm.c:124",
      "file": "security/selinux/xfrm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ],
      "caller_func": [
        "security/selinux/xfrm.c:selinux_xfrm_state_free",
        "security/selinux/xfrm.c:selinux_xfrm_policy_free"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583592240,
      "name": "selinux_xfrm_free.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 23
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
void selinux_xfrm_free(struct xfrm_sec_ctx * ctx)
```
</details>
</li>
</ul>
