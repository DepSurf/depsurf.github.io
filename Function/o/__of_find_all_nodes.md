# Function: <code>__of_find_all_nodes</code>

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
<details>
<summary>In <code>5.4.0-26-generic-arm64</code>: Selective Inline, Transformation ❓</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```

```json
{
  "name": "__of_find_all_nodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446603336501600440,
      "name": "__of_find_all_nodes",
      "external": true,
      "loc": "drivers/of/base.c:287",
      "file": "drivers/of/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501594816,
      "name": "__of_find_all_nodes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 18446603336501602672,
      "name": "__of_find_all_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 88
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: Selective Inline, Transformation ❓</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```

```json
{
  "name": "__of_find_all_nodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 3234123848,
      "name": "__of_find_all_nodes",
      "external": true,
      "loc": "drivers/of/base.c:287",
      "file": "drivers/of/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234123120,
      "name": "__of_find_all_nodes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 56
    },
    {
      "addr": 3234127668,
      "name": "__of_find_all_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 84
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: Selective Inline, Transformation ❓</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```

```json
{
  "name": "__of_find_all_nodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 13835058055295019076,
      "name": "__of_find_all_nodes",
      "external": true,
      "loc": "drivers/of/base.c:287",
      "file": "drivers/of/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295017440,
      "name": "__of_find_all_nodes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 80
    },
    {
      "addr": 13835058055295025632,
      "name": "__of_find_all_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 80
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: Selective Inline, Transformation ❓</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```

```json
{
  "name": "__of_find_all_nodes",
  "collision_type": "Unique Global",
  "inline_type": "Selective",
  "funcs": [
    {
      "addr": 18446743936278065852,
      "name": "__of_find_all_nodes",
      "external": true,
      "loc": "drivers/of/base.c:287",
      "file": "drivers/of/base.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache"
      ],
      "caller_func": [
        "drivers/of/base.c:of_find_node_by_phandle",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_matching_node_and_match",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_node_with_property",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_compatible_node",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_type",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_node_by_name",
        "drivers/of/base.c:of_find_all_nodes",
        "drivers/of/base.c:of_core_init",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/base.c:of_populate_phandle_cache",
        "drivers/of/resolver.c:of_resolve_phandles",
        "drivers/of/resolver.c:of_resolve_phandles"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278065168,
      "name": "__of_find_all_nodes.part.0",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 44
    },
    {
      "addr": 18446743936278069458,
      "name": "__of_find_all_nodes",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 76
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
<b>Arch</b>
<ul>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➕</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * __of_find_all_nodes(struct device_node * prev)
```
</details>
</li>
</ul>
