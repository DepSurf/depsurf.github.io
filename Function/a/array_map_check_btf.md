# Function: <code>array_map_check_btf</code>

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
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, u32 btf_key_id, u32 btf_value_id)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580694768,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:361",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580694768,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 165
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071580766672,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:384",
      "file": "kernel/bpf/arraymap.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580766672,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 53
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580852928,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580852928,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580903968,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580903968,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581049552,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:449",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581049552,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581060928,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:435",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581060928,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581076064,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:435",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581076064,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581303904,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:455",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581303904,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 125
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581602128,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:484",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581602128,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071581982464,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:488",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071581982464,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582173968,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:488",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582173968,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071582322272,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:488",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582322272,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 153
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336492233264,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336492233264,
      "name": "array_map_check_btf",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline ❓</summary>

```c
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3226128904,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3226128904,
      "name": "array_map_check_btf",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline ❓</summary>

```c
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055285459104,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055285459104,
      "name": "array_map_check_btf",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline ❓</summary>

```c
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936272379626,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936272379626,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580872768,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580872768,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580818896,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580818896,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580864016,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580864016,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, const struct btf_type * key_type, const struct btf_type * value_type)
```

```json
{
  "name": "array_map_check_btf",
  "collision_type": "Unique Static",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446744071580922544,
      "name": "array_map_check_btf",
      "external": false,
      "loc": "kernel/bpf/arraymap.c:415",
      "file": "kernel/bpf/arraymap.c",
      "inline": "not declared, inlined",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071580922544,
      "name": "array_map_check_btf",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 131
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
int array_map_check_btf(const struct bpf_map * map, const struct btf * btf, u32 btf_key_id, u32 btf_value_id)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>const struct btf_type * key_type</code>
</li>
<li>
<b>Param added. </b>
<code>const struct btf_type * value_type</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 btf_key_id</code>
</li>
<li>
<b>Param removed. </b>
<code>u32 btf_value_id</code>
</li>
</ul>
</details>
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
