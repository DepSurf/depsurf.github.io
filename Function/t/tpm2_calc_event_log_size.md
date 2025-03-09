# Function: <code>tpm2_calc_event_log_size</code>

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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605117350,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605156761,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071609426280,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071612500109,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071614642298,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071615600256,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
int tpm2_calc_event_log_size(void * data, int count, void * size_info)
```

```json
{
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071617409159,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071617409159,
      "name": "tpm2_calc_event_log_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 578
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
int tpm2_calc_event_log_size(void * data, int count, void * size_info)
```

```json
{
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071628161984,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071628161984,
      "name": "tpm2_calc_event_log_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 659
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
int tpm2_calc_event_log_size(void * data, int count, void * size_info)
```

```json
{
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071619929344,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071619929344,
      "name": "tpm2_calc_event_log_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 658
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
int tpm2_calc_event_log_size(void * data, int count, void * size_info)
```

```json
{
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071622240512,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071622240512,
      "name": "tpm2_calc_event_log_size",
      "section": ".init.text",
      "bind": "STB_LOCAL",
      "size": 658
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
<summary>In <code>5.4.0-26-generic-arm64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446603336511284368,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 3243935832,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
In <code>5.4.0-26-generic-ppc64el</code>: Absent ❓
</li>
<li>
In <code>5.4.0-24-generic-riscv64</code>: Absent ❓
</li>
</ul>
<b>Flavor</b>
<ul>
<li>
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: Absent ❓</summary>

```json
{
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605047199,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605012539,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605133774,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
  "name": "tpm2_calc_event_log_size",
  "collision_type": "Unique Static",
  "inline_type": "Full",
  "funcs": [
    {
      "addr": 18446744071605160955,
      "name": "tpm2_calc_event_log_size",
      "external": false,
      "loc": "drivers/firmware/efi/tpm.c:19",
      "file": "drivers/firmware/efi/tpm.c",
      "inline": "not declared, inlined",
      "caller_inline": [
        "drivers/firmware/efi/tpm.c:efi_tpm_eventlog_init"
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
<summary>Added between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ➕</summary>

```c
int tpm2_calc_event_log_size(void * data, int count, void * size_info)
```
</details>
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
