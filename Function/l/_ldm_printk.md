# Function: <code>_ldm_printk</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071582842288,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:53",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071582842288,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583126240,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:55",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583126240,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583238160,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:55",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583238160,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583291280,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:55",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_get_vstr",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583291280,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583472352,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:55",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_get_vstr",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583472352,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 127
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583692211,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:55",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_get_vstr",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583692211,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583799648,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:55",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_get_vstr",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583799648,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583989772,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583989772,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584093148,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584093148,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584488712,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_parse_vmdb",
        "block/partitions/ldm.c:ldm_parse_vmdb",
        "block/partitions/ldm.c:ldm_parse_vmdb",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584488712,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591373829,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_parse_vmdb",
        "block/partitions/ldm.c:ldm_parse_vmdb",
        "block/partitions/ldm.c:ldm_parse_vmdb",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591373829,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591316489,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591316489,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071592316856,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_get_vnum",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071592316856,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071594101409,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_get_vnum",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071594101409,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 171
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586542896,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_get_vnum",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586542896,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071586793680,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_get_vnum",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071586793680,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587070512,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_frag_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_get_vnum",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_create_data_partitions",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_vmdb",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock",
        "block/partitions/ldm.c:ldm_parse_tocblock"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587070512,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 158
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336495938148,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_parse_prt3",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead",
        "block/partitions/ldm.c:ldm_parse_privhead"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336495938148,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 156
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3229281372,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3229281372,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 136
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055290155076,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_ldmdb_add",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_get_vstr",
        "block/partitions/ldm.c:ldm_get_vnum",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055290155076,
      "name": "_ldm_printk",
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
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936275049510,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936275049510,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 102
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584061884,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584061884,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071583997644,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071583997644,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584045644,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584045644,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
void _ldm_printk(const char * level, const char * function, const char * fmt, void (anon))
```

```json
{
  "name": "_ldm_printk",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584148140,
      "name": "_ldm_printk",
      "external": false,
      "loc": "block/partitions/ldm.c:41",
      "file": "block/partitions/ldm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_partition",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_get_vblks",
        "block/partitions/ldm.c:ldm_ldmdb_add",
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
        "block/partitions/ldm.c:ldm_parse_vol5",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_relative",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_tocblocks",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads",
        "block/partitions/ldm.c:ldm_validate_privheads"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584148140,
      "name": "_ldm_printk",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 129
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
