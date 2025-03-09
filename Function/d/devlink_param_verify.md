# Function: <code>devlink_param_verify</code>

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
<summary>In <code>5.3.0-18-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588612729,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6292",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588835641,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589715482,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:7934",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589744346,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:8822",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071589629690,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:9085",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
<summary>In <code>5.15.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
int devlink_param_verify(const struct devlink_param * param)
```

```json
{
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:9930",
      "file": "net/core/devlink.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/core/devlink.c:devlink_param_register",
        "net/core/devlink.c:__devlink_params_register"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590315984,
      "name": "devlink_param_verify",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 332
    },
    {
      "addr": 18446744071592706964,
      "name": "devlink_param_verify.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 20
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: Absent ❓</summary>

```json
{
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071591917271,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:10798",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_param_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071593722391,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:11581",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:devlink_param_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071595866225,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/devlink/leftover.c:8138",
      "file": "net/devlink/leftover.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/leftover.c:devl_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071596731328,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/devlink/param.c:612",
      "file": "net/devlink/param.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/devlink/param.c:devl_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336502408568,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3235145112,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 13835058055295956616,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446743936278616644,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588442025,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588154713,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588774201,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
  "name": "devlink_param_verify",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071588914729,
      "name": "devlink_param_verify",
      "external": false,
      "loc": "net/core/devlink.c:6989",
      "file": "net/core/devlink.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "net/core/devlink.c:__devlink_params_register"
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
<summary>Added between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ➕</summary>

```c
int devlink_param_verify(const struct devlink_param * param)
```
</details>
</li>
<li>
<details>
<summary>Removed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➖</summary>

```c
int devlink_param_verify(const struct devlink_param * param)
```
</details>
</li>
</ul>
