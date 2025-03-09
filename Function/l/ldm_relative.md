# Function: <code>ldm_relative</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582842432,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:687",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842432,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 253
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583126384,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:635",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126384,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238304,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:635",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238304,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 248
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291408,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:635",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291408,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583472480,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:635",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583472480,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 243
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:635",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583685312,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583692340,
      "name": "ldm_relative.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:635",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583792608,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 145
    },
    {
      "addr": 18446744071583799777,
      "name": "ldm_relative.cold.8",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 96
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583982528,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 115
    },
    {
      "addr": 18446744071583989901,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584085904,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071584093277,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_dsk4",
        "block/partitions/ldm.c:ldm_parse_dsk4",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584481424,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071584489258,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_dsk4",
        "block/partitions/ldm.c:ldm_parse_dsk4",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dsk3",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr4",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_dgr3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584594816,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071591374375,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584626432,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071591316731,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585042176,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071592316985,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585761280,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 135
    },
    {
      "addr": 18446744071594101580,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 117
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586543488,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586543488,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586794272,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586794272,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587071104,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vblk",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3",
        "block/partitions/ldm.c:ldm_parse_cmp3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587071104,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 235
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495928408,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495928408,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 320
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229271736,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229271736,
      "name": "ldm_relative",
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
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290143376,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290143376,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 440
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
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275040362,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275040362,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 244
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584054640,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071584062013,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583990400,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071583997773,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584038400,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071584045773,
      "name": "ldm_relative.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 132
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: Transformation ❓</summary>

```c
int ldm_relative(const u8 * buffer, int buflen, int base, int offset)
```

```json
{
  "name": "ldm_relative",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "ldm_relative",
      "external": false,
      "loc": "block/partitions/ldm.c:621",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584140896,
      "name": "ldm_relative",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 119
    },
    {
      "addr": 18446744071584148269,
      "name": "ldm_relative.cold",
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
