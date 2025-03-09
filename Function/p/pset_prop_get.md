# Function: <code>pset_prop_get</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct property_entry * pset_prop_get(struct property_set * pset, const char * name)
```

```json
{
  "name": "pset_prop_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584419616,
      "name": "pset_prop_get",
      "external": false,
      "loc": "drivers/base/property.c:33",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:pset_prop_find",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:__fwnode_property_read_string_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u32_array"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584419616,
      "name": "pset_prop_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct property_entry * pset_prop_get(struct property_set * pset, const char * name)
```

```json
{
  "name": "pset_prop_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584754976,
      "name": "pset_prop_get",
      "external": false,
      "loc": "drivers/base/property.c:38",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:__fwnode_property_read_string",
        "drivers/base/property.c:__fwnode_property_read_string_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:__fwnode_property_present",
        "drivers/base/property.c:pset_prop_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584754976,
      "name": "pset_prop_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
struct property_entry * pset_prop_get(struct property_set * pset, const char * name)
```

```json
{
  "name": "pset_prop_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071584945200,
      "name": "pset_prop_get",
      "external": false,
      "loc": "drivers/base/property.c:38",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:__fwnode_property_read_string",
        "drivers/base/property.c:__fwnode_property_read_string_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u64_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u32_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u16_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:fwnode_property_read_u8_array",
        "drivers/base/property.c:__fwnode_property_present",
        "drivers/base/property.c:pset_prop_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071584945200,
      "name": "pset_prop_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
const struct property_entry * pset_prop_get(struct property_set * pset, const char * name)
```

```json
{
  "name": "pset_prop_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585031616,
      "name": "pset_prop_get",
      "external": false,
      "loc": "drivers/base/property.c:39",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:pset_fwnode_property_read_string_array",
        "drivers/base/property.c:pset_fwnode_read_int_array",
        "drivers/base/property.c:pset_fwnode_property_present",
        "drivers/base/property.c:pset_prop_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585031616,
      "name": "pset_prop_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
const struct property_entry * pset_prop_get(const struct property_set * pset, const char * name)
```

```json
{
  "name": "pset_prop_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585454384,
      "name": "pset_prop_get",
      "external": false,
      "loc": "drivers/base/property.c:47",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:pset_fwnode_property_read_string_array",
        "drivers/base/property.c:pset_fwnode_read_int_array",
        "drivers/base/property.c:pset_fwnode_property_present",
        "drivers/base/property.c:pset_fwnode_property_present",
        "drivers/base/property.c:pset_prop_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585454384,
      "name": "pset_prop_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
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
const struct property_entry * pset_prop_get(const struct property_set * pset, const char * name)
```

```json
{
  "name": "pset_prop_get",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071585697360,
      "name": "pset_prop_get",
      "external": false,
      "loc": "drivers/base/property.c:45",
      "file": "drivers/base/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/base/property.c:pset_fwnode_property_read_string_array",
        "drivers/base/property.c:pset_fwnode_read_int_array",
        "drivers/base/property.c:pset_fwnode_property_present",
        "drivers/base/property.c:pset_fwnode_property_present",
        "drivers/base/property.c:pset_prop_find"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071585697360,
      "name": "pset_prop_get",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 81
    }
  ]
}
```
</details>
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
In <code>6.2.0-20-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.5.0-9-generic-amd64</code>: Absent ❓
</li>
<li>
In <code>6.8.0-31-generic-amd64</code>: Absent ❓
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
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Return type changed. </b>
<code>struct property_entry *</code> ➡️ <code>const struct property_entry *</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param type changed. </b>
<code>struct property_set * pset</code> ➡️ <code>const struct property_set * pset</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ➖</summary>

```c
const struct property_entry * pset_prop_get(const struct property_set * pset, const char * name)
```
</details>
</li>
</ul>
