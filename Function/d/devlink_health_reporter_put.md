# Function: <code>devlink_health_reporter_put</code>

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
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588569744,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4862",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588569744,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588786720,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588786720,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589699671,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:5512",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
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
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589695376,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:5991",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_port_health_reporter_destroy",
        "net/core/devlink.c:devlink_health_reporter_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589695376,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589576112,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:6194",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_port_health_reporter_destroy",
        "net/core/devlink.c:devlink_health_reporter_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589576112,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590326320,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:6807",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_port_health_reporter_destroy",
        "net/core/devlink.c:devlink_health_reporter_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590326320,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 184
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591924576,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:7299",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_port_health_reporter_destroy",
        "net/core/devlink.c:devlink_health_reporter_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591924576,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593730768,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:7854",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_test_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit",
        "net/core/devlink.c:devlink_port_health_reporter_destroy",
        "net/core/devlink.c:devlink_health_reporter_destroy"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593730768,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 218
    }
  ]
}
```
</details>
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502361924,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
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
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235099764,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
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
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295891000,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
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
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278577770,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
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
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588393104,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588393104,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588105792,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588105792,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588725280,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588725280,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```

```json
{
  "name": "devlink_health_reporter_put",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588865696,
      "name": "devlink_health_reporter_put",
      "external": false,
      "loc": "net/core/devlink.c:4918",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_clear_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_dump_get_dumpit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_diagnose_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_recover_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_set_doit",
        "net/core/devlink.c:devlink_nl_cmd_health_reporter_get_doit"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588865696,
      "name": "devlink_health_reporter_put",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 30
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
<summary>Added between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ➕</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➖</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
</li>
<li>
<details>
<summary>Added between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ➕</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
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
<details>
<summary>Removed between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ➖</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
</li>
</ul>
<b>Arch</b>
<ul>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ➖</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ➖</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ➖</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ➖</summary>

```c
void devlink_health_reporter_put(struct devlink_health_reporter * reporter)
```
</details>
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
