# Function: <code>of_graph_get_next_endpoint</code>

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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```

```json
{
  "name": "of_graph_get_next_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501620776,
      "name": "of_graph_get_next_endpoint",
      "external": true,
      "loc": "drivers/of/property.c:595",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display",
        "drivers/of/property.c:of_fwnode_graph_get_next_endpoint",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501620776,
      "name": "of_graph_get_next_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 304
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
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```

```json
{
  "name": "of_graph_get_next_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234143672,
      "name": "of_graph_get_next_endpoint",
      "external": true,
      "loc": "drivers/of/property.c:595",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/video/fbdev/amba-clcd.c:clcdfb_of_init_display",
        "drivers/video/fbdev/omap2/omapfb/dss/omapdss-boot-init.c:omapdss_walk_device",
        "drivers/of/property.c:of_fwnode_graph_get_next_endpoint",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234143672,
      "name": "of_graph_get_next_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 312
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
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```

```json
{
  "name": "of_graph_get_next_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295049968,
      "name": "of_graph_get_next_endpoint",
      "external": true,
      "loc": "drivers/of/property.c:595",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/property.c:of_fwnode_graph_get_next_endpoint",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295049968,
      "name": "of_graph_get_next_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 452
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
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```

```json
{
  "name": "of_graph_get_next_endpoint",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278082984,
      "name": "of_graph_get_next_endpoint",
      "external": true,
      "loc": "drivers/of/property.c:595",
      "file": "drivers/of/property.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/property.c:of_fwnode_graph_get_next_endpoint",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_count",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs",
        "drivers/of/property.c:of_graph_get_endpoint_by_regs"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278082984,
      "name": "of_graph_get_next_endpoint",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 266
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
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
struct device_node * of_graph_get_next_endpoint(const struct device_node * parent, struct device_node * prev)
```
</details>
</li>
</ul>
