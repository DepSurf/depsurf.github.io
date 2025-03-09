# Function: <code>opp_migrate_dentry</code>

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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587063237,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:185",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
<summary>In <code>4.18.0-10-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587361461,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:196",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
<summary>In <code>5.0.0-13-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587541333,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:196",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587815956,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588021156,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void opp_migrate_dentry(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:187",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588880576,
      "name": "opp_migrate_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071588881323,
      "name": "opp_migrate_dentry.cold",
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void opp_migrate_dentry(struct opp_device * opp_dev, struct opp_table * opp_table)
```

```json
{
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:187",
      "file": "drivers/opp/debugfs.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588893520,
      "name": "opp_migrate_dentry",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 137
    },
    {
      "addr": 18446744071591597667,
      "name": "opp_migrate_dentry.cold",
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588783141,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:187",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589475381,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:187",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071590954661,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:195",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071592656981,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:214",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593087717,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:213",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593840117,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:213",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336501284080,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3233772628,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055294809832,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936277957690,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587646148,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587420020,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071587977300,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
  "name": "opp_migrate_dentry",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588092676,
      "name": "opp_migrate_dentry",
      "external": false,
      "loc": "drivers/opp/debugfs.c:145",
      "file": "drivers/opp/debugfs.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/opp/debugfs.c:opp_debug_unregister"
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void opp_migrate_dentry(struct opp_device * opp_dev, struct opp_table * opp_table)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ➖</summary>

```c
void opp_migrate_dentry(struct opp_device * opp_dev, struct opp_table * opp_table)
```
</details>
</li>
</ul>
