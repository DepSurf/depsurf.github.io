# Function: <code>ncsi_find_package_and_channel</code>

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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071587819648,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:387",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071587819648,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588033664,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:407",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588033664,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588191760,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:407",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588191760,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071588738384,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:432",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071588738384,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589104752,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:306",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589104752,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 143
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589333920,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:329",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589333920,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 154
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589789136,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:325",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589789136,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590012416,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590012416,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591044256,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:326",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591044256,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
    }
  ]
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591107872,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:326",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591107872,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591038272,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:332",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591038272,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071591880256,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:332",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071591880256,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 138
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071593599392,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:332",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071593599392,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071595527136,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:332",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071595527136,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596035680,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:332",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596035680,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071596900352,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:332",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071596900352,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 158
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
<summary>In <code>5.4.0-26-generic-arm64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446603336503759680,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446603336503759680,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 208
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 3236384404,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 3236384404,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 176
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 13835058055297600336,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 13835058055297600336,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 200
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446743936279675774,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446743936279675774,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 156
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
<details>
<summary>In <code>5.4.0-1009-aws-amd64</code>: ✅</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589616016,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589616016,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071589340544,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071589340544,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590058048,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590058048,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```

```json
{
  "name": "ncsi_find_package_and_channel",
  "collision_type": "Unique Global",
  "inline_type": "No",
  "funcs": [
    {
      "addr": 18446744071590108144,
      "name": "ncsi_find_package_and_channel",
      "external": true,
      "loc": "net/ncsi/ncsi-manage.c:324",
      "file": "net/ncsi/ncsi-manage.c",
      "inline": "seen, unknown",
      "caller_inline": [],
      "caller_func": [
        "net/ncsi/ncsi-rsp.c:ncsi_rcv_rsp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gpuuid",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gnpts",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gns",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gcps",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gvi",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_snfc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dgmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_egmf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dbf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ebf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sma",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dv",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ev",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_svf",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_gls",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sl",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ae",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dcnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ecnt",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_rc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dc",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_ec",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_dp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_sp",
        "net/ncsi/ncsi-rsp.c:ncsi_rsp_handler_cis",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_hncdsc",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_cr",
        "net/ncsi/ncsi-aen.c:ncsi_aen_handler_lsc",
        "net/ncsi/ncsi-manage.c:ncsi_request_timeout"
      ]
    }
  ],
  "symbols": [
    {
      "addr": 18446744071590108144,
      "name": "ncsi_find_package_and_channel",
      "section": ".text",
      "bind": "STB_GLOBAL",
      "size": 135
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
<summary>Added between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ➕</summary>

```c
void ncsi_find_package_and_channel(struct ncsi_dev_priv * ndp, unsigned char id, struct ncsi_package * * np, struct ncsi_channel * * nc)
```
</details>
</li>
<li>
No changes between <code>4.8.0-22-generic-amd64</code> and <code>4.10.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.10.0-19-generic-amd64</code> and <code>4.13.0-16-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.13.0-16-generic-amd64</code> and <code>4.15.0-20-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ✅
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
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
<b>Arch</b>
<ul>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-arm64</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-armhf</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-26-generic-ppc64el</code> ✅
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.4.0-24-generic-riscv64</code> ✅
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
