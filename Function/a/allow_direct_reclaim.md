# Function: <code>allow_direct_reclaim</code>

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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580768518,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:2885",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580750016,
      "name": "allow_direct_reclaim.part.55",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580855855,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:2909",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:kswapd",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580837264,
      "name": "allow_direct_reclaim.part.58",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580992863,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:2918",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580973904,
      "name": "allow_direct_reclaim.part.52",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 212
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581070063,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3085",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581050576,
      "name": "allow_direct_reclaim.part.54",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581133512,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3046",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581114144,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581191256,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581171104,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581375005,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3105",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581363664,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581418765,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3109",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581407264,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581439968,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3307",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581428496,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581693511,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3468",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581680672,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 247
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
bool allow_direct_reclaim(pg_data_t * pgdat)
```

```json
{
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582057424,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3611",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582057424,
      "name": "allow_direct_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
bool allow_direct_reclaim(pg_data_t * pgdat)
```

```json
{
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582530096,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:6547",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582530096,
      "name": "allow_direct_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
bool allow_direct_reclaim(pg_data_t * pgdat)
```

```json
{
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582733376,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:6910",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582733376,
      "name": "allow_direct_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
bool allow_direct_reclaim(pg_data_t * pgdat)
```

```json
{
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582901296,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:6277",
      "file": "mm/vmscan.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582901296,
      "name": "allow_direct_reclaim",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 441
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492572368,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492550864,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 280
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226434952,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages",
        "mm/vmscan.c:try_to_free_pages"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3226414436,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 152
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285881592,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285853360,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 268
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272613824,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272597102,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 246
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581160104,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581139952,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581106968,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581086896,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581151304,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581131152,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
  "name": "allow_direct_reclaim",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581214040,
      "name": "allow_direct_reclaim",
      "external": false,
      "loc": "mm/vmscan.c:3132",
      "file": "mm/vmscan.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ],
      "caller_func": [
        "mm/vmscan.c:balance_pgdat",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim",
        "mm/vmscan.c:throttle_direct_reclaim"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581193616,
      "name": "allow_direct_reclaim.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 221
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
bool allow_direct_reclaim(pg_data_t * pgdat)
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
