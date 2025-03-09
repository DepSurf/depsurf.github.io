# Function: <code>cpufreq_governor_limits</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585880277,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq_governor.c:506",
      "file": "drivers/cpufreq/cpufreq_governor.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq_governor.c:cpufreq_governor_dbs"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586256173,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2097",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586255984,
      "name": "cpufreq_governor_limits.part.13",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586465311,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2069",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586460336,
      "name": "cpufreq_governor_limits.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071586590127,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2072",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586584944,
      "name": "cpufreq_governor_limits.part.11",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 70
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587073103,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2105",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587068240,
      "name": "cpufreq_governor_limits.part.12",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 73
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Selective Inline ❓</summary>

```c
void cpufreq_governor_limits(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587365760,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2104",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587365760,
      "name": "cpufreq_governor_limits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
void cpufreq_governor_limits(struct cpufreq_policy * policy)
```

```json
{
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071587545648,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2105",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": [
        "drivers/cpufreq/cpufreq.c:cpufreq_boost_set_sw",
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587545648,
      "name": "cpufreq_governor_limits",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 92
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587829097,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2255",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588034385,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588895568,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2306",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588907533,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2382",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588795635,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2388",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589487966,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2390",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590969755,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2430",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592674083,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2427",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593104899,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2434",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593857677,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2475",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501301536,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233789656,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294832196,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587659377,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587433249,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587990529,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
  "name": "cpufreq_governor_limits",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588105949,
      "name": "cpufreq_governor_limits",
      "external": false,
      "loc": "drivers/cpufreq/cpufreq.c:2269",
      "file": "drivers/cpufreq/cpufreq.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/cpufreq/cpufreq.c:cpufreq_set_policy"
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
<summary>Added between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ➕</summary>

```c
void cpufreq_governor_limits(struct cpufreq_policy * policy)
```
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➖</summary>

```c
void cpufreq_governor_limits(struct cpufreq_policy * policy)
```
</details>
</li>
</ul>
