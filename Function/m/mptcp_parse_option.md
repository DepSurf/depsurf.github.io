# Function: <code>mptcp_parse_option</code>

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
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:20",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591101296,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1482
    },
    {
      "addr": 18446744071591107031,
      "name": "mptcp_parse_option.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: Transformation ❓</summary>

```c
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 0,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:21",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591181344,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1552
    },
    {
      "addr": 18446744071591640879,
      "name": "mptcp_parse_option.cold",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 21
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
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591117440,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:23",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591117440,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 1745
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
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591963216,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:23",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591963216,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2046
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
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593691408,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:23",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593691408,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2145
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
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595625216,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:23",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595625216,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2122
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
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596133552,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:23",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596133552,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2081
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
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```

```json
{
  "name": "mptcp_parse_option",
  "collision_type": "Unique Static",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071597007280,
      "name": "mptcp_parse_option",
      "external": false,
      "loc": "net/mptcp/options.c:23",
      "file": "net/mptcp/options.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/mptcp/options.c:mptcp_get_options"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071597007280,
      "name": "mptcp_parse_option",
      "section": ".text",
      "bind": "STB_LOCAL",
      "size": 2075
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
<summary>Added between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ➕</summary>

```c
void mptcp_parse_option(const struct sk_buff * skb, const unsigned char * ptr, int opsize, struct mptcp_options_received * mp_opt)
```
</details>
</li>
<li>
No changes between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ✅
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
No changes between <code>6.2.0-20-generic-amd64</code> and <code>6.5.0-9-generic-amd64</code> ✅
</li>
<li>
No changes between <code>6.5.0-9-generic-amd64</code> and <code>6.8.0-31-generic-amd64</code> ✅
</li>
</ul>
