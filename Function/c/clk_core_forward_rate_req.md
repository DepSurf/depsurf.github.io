# Function: <code>clk_core_forward_rate_req</code>

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
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
void clk_core_forward_rate_req(struct clk_core * core, const struct clk_rate_request * old_req, struct clk_core * parent, struct clk_rate_request * req, long unsigned int parent_rate)
```

```json
{
  "name": "clk_core_forward_rate_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589299040,
      "name": "clk_core_forward_rate_req",
      "external": false,
      "loc": "drivers/clk/clk.c:568",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_hw_forward_rate_request",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589299040,
      "name": "clk_core_forward_rate_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void clk_core_forward_rate_req(struct clk_core * core, const struct clk_rate_request * old_req, struct clk_core * parent, struct clk_rate_request * req, long unsigned int parent_rate)
```

```json
{
  "name": "clk_core_forward_rate_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589596176,
      "name": "clk_core_forward_rate_req",
      "external": false,
      "loc": "drivers/clk/clk.c:579",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_hw_forward_rate_request",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589596176,
      "name": "clk_core_forward_rate_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void clk_core_forward_rate_req(struct clk_core * core, const struct clk_rate_request * old_req, struct clk_core * parent, struct clk_rate_request * req, long unsigned int parent_rate)
```

```json
{
  "name": "clk_core_forward_rate_req",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589905952,
      "name": "clk_core_forward_rate_req",
      "external": false,
      "loc": "drivers/clk/clk.c:579",
      "file": "drivers/clk/clk.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "drivers/clk/clk.c:clk_core_round_rate_nolock",
        "drivers/clk/clk.c:clk_hw_forward_rate_request",
        "drivers/clk/clk.c:clk_mux_determine_rate_flags"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589905952,
      "name": "clk_core_forward_rate_req",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 196
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
void clk_core_forward_rate_req(struct clk_core * core, const struct clk_rate_request * old_req, struct clk_core * parent, struct clk_rate_request * req, long unsigned int parent_rate)
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
