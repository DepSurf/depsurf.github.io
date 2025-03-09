# Function: <code>destroy_ns</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void destroy_ns(struct aa_ns * ns)
```

```json
{
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582600256,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:250",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:__aa_remove_ns",
        "security/apparmor/policy_ns.c:aa_free_root_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582600256,
      "name": "destroy_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 160
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
void destroy_ns(struct aa_ns * ns)
```

```json
{
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582844512,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:276",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582844512,
      "name": "destroy_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
void destroy_ns(struct aa_ns * ns)
```

```json
{
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582940512,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:277",
      "file": "security/apparmor/policy_ns.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582940512,
      "name": "destroy_ns",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 198
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071596558389,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:334",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582959184,
      "name": "destroy_ns.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071602885843,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:334",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583121376,
      "name": "destroy_ns.part.4",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 188
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071603058735,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:334",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583327056,
      "name": "destroy_ns.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604859527,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:334",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583445616,
      "name": "destroy_ns.part.6",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 183
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604964591,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583630640,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605000155,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583736816,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071609280620,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584121024,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071612349495,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584239808,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071614490453,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584264816,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071615437415,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584650768,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071617235025,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:345",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585308304,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071627947784,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:344",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586047696,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071619711048,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:344",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586282704,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071622018136,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:307",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:aa_alloc_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586539168,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 200
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336511044100,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495534168,
      "name": "destroy_ns.part.0",
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
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Absent ❓</summary>

```json
{
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3243525740,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3228899976,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 180
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055302718844,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055289616384,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 272
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Absent ❓</summary>

```json
{
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936270756344,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936274709880,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 190
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604905615,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583705552,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604874667,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583642608,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071604982787,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583689328,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
  "name": "destroy_ns",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071605004325,
      "name": "destroy_ns",
      "external": false,
      "loc": "security/apparmor/policy_ns.c:330",
      "file": "security/apparmor/policy_ns.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ],
      "caller_func": [
        "security/apparmor/policy_ns.c:aa_free_root_ns",
        "security/apparmor/policy_ns.c:__aa_remove_ns"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583789216,
      "name": "destroy_ns.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 192
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
void destroy_ns(struct aa_ns * ns)
```
</details>
</li>
</ul>
