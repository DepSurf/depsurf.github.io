# Function: <code>dev_pm_opp_get</code>

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
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587057224,
      "name": "dev_pm_opp_get",
      "external": false,
      "loc": "drivers/opp/core.c:916",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587355640,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:923",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587357584,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587535080,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1022",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587537312,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587809013,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1096",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587811344,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588014181,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588016720,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588876191,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1208",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588874384,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588884879,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1277",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588890320,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588772479,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1434",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588777232,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071589464447,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1444",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589469328,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 66
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
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071590942147,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1589",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:dev_pm_opp_find_bw_floor",
        "drivers/opp/core.c:dev_pm_opp_find_bw_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_ceil_by_volt",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590948112,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071592644051,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1561",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_opp_table_find_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592649328,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593074547,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1569",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_opp_table_find_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593079904,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071593826467,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1679",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:dev_pm_opp_adjust_voltage",
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_xlate_required_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_set_opp",
        "drivers/opp/core.c:_opp_table_find_key"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593832112,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 108
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501270844,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": [
        "drivers/opp/of.c:_find_opp_of_np"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501273928,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 44
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3233760864,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": [
        "drivers/opp/of.c:_find_opp_of_np"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3233763600,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055294792648,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": [
        "drivers/opp/of.c:_find_opp_of_np"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294796432,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 32
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936277946936,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": [
        "drivers/opp/of.c:_find_opp_of_np"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277949566,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 42
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587639173,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587641712,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587413045,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587415584,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587970325,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587972864,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Selective Inline ❓</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```

```json
{
  "name": "dev_pm_opp_get",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071588085701,
      "name": "dev_pm_opp_get",
      "external": true,
      "loc": "drivers/opp/core.c:1145",
      "file": "drivers/opp/core.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/core.c:_opp_set_availability",
        "drivers/opp/core.c:dev_pm_opp_find_freq_floor",
        "drivers/opp/core.c:_find_freq_ceil",
        "drivers/opp/core.c:dev_pm_opp_find_level_exact",
        "drivers/opp/core.c:dev_pm_opp_find_freq_exact"
      ],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588088240,
      "name": "dev_pm_opp_get",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 21
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void dev_pm_opp_get(struct dev_pm_opp * opp)
```
</details>
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
