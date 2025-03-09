# Function: <code>dm_table_set_type</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071585817253,
      "name": "dm_table_set_type",
      "external": false,
      "loc": "drivers/md/dm-table.c:821",
      "file": "drivers/md/dm-table.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/md/dm-table.c:dm_table_complete"
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
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table * t, unsigned int type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586205120,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:842",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586205120,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, unsigned int type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586409584,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:836",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586409584,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586512880,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:876",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586512880,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586980304,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:878",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586980304,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587277536,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:879",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587277536,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587457744,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:877",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587457744,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587731168,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:877",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587731168,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587935456,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587935456,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588787888,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:858",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588787888,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588806032,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:816",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588806032,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588691728,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:802",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588691728,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589379776,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:802",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589379776,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590855664,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:803",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590855664,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592546944,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:802",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592546944,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592978192,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:797",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592978192,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593728176,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:818",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593728176,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 22
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501173248,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501173248,
      "name": "dm_table_set_type",
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
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3233680876,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 3233680876,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 28
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055294683872,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 13835058055294683872,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 16
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936277878340,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446743936277878340,
      "name": "dm_table_set_type",
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587566432,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587566432,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587334512,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587334512,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587891600,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587891600,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
void dm_table_set_type(struct dm_table * t, enum dm_queue_mode type)
```

```json
{
  "name": "dm_table_set_type",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588006864,
      "name": "dm_table_set_type",
      "external": true,
      "loc": "drivers/md/dm-table.c:875",
      "file": "drivers/md/dm-table.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": []
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588006864,
      "name": "dm_table_set_type",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 14
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void dm_table_set_type(struct dm_table * t, unsigned int type)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>unsigned int type</code> ➡️ <code>enum dm_queue_mode type</code>
</li>
</ul>
</details>
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
