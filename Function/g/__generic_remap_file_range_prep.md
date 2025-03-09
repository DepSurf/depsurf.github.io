# Function: <code>__generic_remap_file_range_prep</code>

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
In <code>4.18.0-10-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.0.0-13-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.3.0-18-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.8.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.11.0-16-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.13.0-19-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.15.0-25-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>5.19.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: Transformation ❓</summary>

```c
int __generic_remap_file_range_prep(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * len, unsigned int remap_flags, const struct iomap_ops * dax_read_ops)
```

```json
{
  "name": "__generic_remap_file_range_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__generic_remap_file_range_prep",
      "external": true,
      "loc": "fs/remap_range.c:268",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/dax.c:dax_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596052008,
      "name": "__generic_remap_file_range_prep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071583896544,
      "name": "__generic_remap_file_range_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 653
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: Transformation ❓</summary>

```c
int __generic_remap_file_range_prep(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * len, unsigned int remap_flags, const struct iomap_ops * dax_read_ops)
```

```json
{
  "name": "__generic_remap_file_range_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__generic_remap_file_range_prep",
      "external": true,
      "loc": "fs/remap_range.c:271",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/dax.c:dax_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596574536,
      "name": "__generic_remap_file_range_prep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584119632,
      "name": "__generic_remap_file_range_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: Transformation ❓</summary>

```c
int __generic_remap_file_range_prep(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * len, unsigned int remap_flags, const struct iomap_ops * dax_read_ops)
```

```json
{
  "name": "__generic_remap_file_range_prep",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "__generic_remap_file_range_prep",
      "external": true,
      "loc": "fs/remap_range.c:277",
      "file": "fs/remap_range.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "fs/remap_range.c:generic_remap_file_range_prep",
        "fs/dax.c:dax_remap_file_range_prep"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597479207,
      "name": "__generic_remap_file_range_prep.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 54
    },
    {
      "addr": 18446744071584336272,
      "name": "__generic_remap_file_range_prep",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 659
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
In <code>5.4.0-26-generic-arm64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-armhf</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
In <code>5.4.0-1009-aws-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1010-azure-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-1009-gcp-amd64</code>: Absent ❓
</li>
<li>
In <code>5.4.0-26-lowlatency-amd64</code>: Absent ❓
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
<details>
<summary>Added between <code>5.19.0-21-generic-amd64</code> and <code>6.2.0-20-generic-amd64</code> ➕</summary>

```c
int __generic_remap_file_range_prep(struct file * file_in, loff_t pos_in, struct file * file_out, loff_t pos_out, loff_t * len, unsigned int remap_flags, const struct iomap_ops * dax_read_ops)
```
</details>
</li>
<li>
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
