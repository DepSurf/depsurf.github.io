# Function: <code>of_platform_bus_create</code>

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
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```

```json
{
  "name": "of_platform_bus_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336501614488,
      "name": "of_platform_bus_create",
      "external": false,
      "loc": "drivers/of/platform.c:346",
      "file": "drivers/of/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336501614488,
      "name": "of_platform_bus_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1248
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
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```

```json
{
  "name": "of_platform_bus_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3234137596,
      "name": "of_platform_bus_create",
      "external": false,
      "loc": "drivers/of/platform.c:346",
      "file": "drivers/of/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3234137596,
      "name": "of_platform_bus_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1312
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
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```

```json
{
  "name": "of_platform_bus_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055295041472,
      "name": "of_platform_bus_create",
      "external": false,
      "loc": "drivers/of/platform.c:346",
      "file": "drivers/of/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055295041472,
      "name": "of_platform_bus_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1100
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
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```

```json
{
  "name": "of_platform_bus_create",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936278078382,
      "name": "of_platform_bus_create",
      "external": false,
      "loc": "drivers/of/platform.c:346",
      "file": "drivers/of/platform.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/of/platform.c:of_platform_populate",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_probe",
        "drivers/of/platform.c:of_platform_bus_create"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936278078382,
      "name": "of_platform_bus_create",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 732
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
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➕</summary>

```c
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➕</summary>

```c
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➕</summary>

```c
int of_platform_bus_create(struct device_node * bus, const struct of_device_id * matches, const struct of_dev_auxdata * lookup, struct device * parent, bool strict)
```
</details>
</li>
</ul>
