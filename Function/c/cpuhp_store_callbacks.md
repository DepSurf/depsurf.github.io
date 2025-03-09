# Function: <code>cpuhp_store_callbacks</code>

## Status
<b>Regular</b>
<ul>
<li>
In <code>4.4.0-21-generic-amd64</code>: Absent ❓
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
void cpuhp_store_callbacks(enum cpuhp_state state, const char * name, int (*)(unsigned int) startup, int (*)(unsigned int) teardown)
```

```json
{
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579383392,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1376",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579383392,
      "name": "cpuhp_store_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 104
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
int cpuhp_store_callbacks(enum cpuhp_state state, const char * name, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```

```json
{
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071579402800,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1327",
      "file": "kernel/cpu.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "kernel/cpu.c:__cpuhp_remove_state",
        "kernel/cpu.c:__cpuhp_setup_state",
        "kernel/cpu.c:__cpuhp_setup_state"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071579402800,
      "name": "cpuhp_store_callbacks",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 287
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579395555,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1246",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
<summary>In <code>4.15.0-20-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579423316,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1430",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579438122,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1512",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579471082,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1534",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579488889,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1560",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579514825,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579543640,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1706",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579525352,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1717",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
<summary>In <code>5.13.0-19-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579529016,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1821",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579601075,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1851",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579693409,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1873",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579817391,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1897",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579865407,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:2282",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579903311,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:2328",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336490651608,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3224728100,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055283473408,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936271399884,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579488489,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579417369,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579488409,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
  "name": "cpuhp_store_callbacks",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071579520713,
      "name": "cpuhp_store_callbacks",
      "external": false,
      "loc": "kernel/cpu.c:1575",
      "file": "kernel/cpu.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "kernel/cpu.c:__cpuhp_remove_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked",
        "kernel/cpu.c:__cpuhp_setup_state_cpuslocked"
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void cpuhp_store_callbacks(enum cpuhp_state state, const char * name, int (*)(unsigned int) startup, int (*)(unsigned int) teardown)
```
</details>
</li>
<li>
<details>
<summary>Changed between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Param added. </b>
<code>bool multi_instance</code>
</li>
<li>
<b>Return type changed. </b>
<code>void</code> ➡️ <code>int</code>
</li>
</ul>
</details>
</li>
<li>
<details>
<summary>Removed between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ➖</summary>

```c
int cpuhp_store_callbacks(enum cpuhp_state state, const char * name, int (*)(unsigned int) startup, int (*)(unsigned int) teardown, bool multi_instance)
```
</details>
</li>
</ul>
