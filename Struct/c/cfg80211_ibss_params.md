# Struct: <code>cfg80211_ibss_params</code>

## Status
<b>Regular</b>
<ul>
<li>
<details>
<summary>In <code>4.4.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.8.0-22-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.10.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.13.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.15.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>4.18.0-10-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.0.0-13-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.3.0-18-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[3] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.8.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.11.0-16-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[5] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.13.0-19-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[5] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.15.0-25-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[5] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.19.0-21-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[6] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.2.0-20-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[6] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.5.0-9-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[6] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>6.8.0-31-generic-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[6] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
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
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-armhf</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-generic-ppc64el</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-24-generic-riscv64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
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
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1010-azure-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-1009-gcp-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
<li>
<details>
<summary>In <code>5.4.0-26-lowlatency-amd64</code>: ✅</summary>

```c
struct cfg80211_ibss_params {
    const u8 * ssid;
    const u8 * bssid;
    struct cfg80211_chan_def chandef;
    const u8 * ie;
    u8 ssid_len;
    u8 ie_len;
    u16 beacon_interval;
    u32 basic_rates;
    bool channel_fixed;
    bool privacy;
    bool control_port;
    bool control_port_over_nl80211;
    bool userspace_handles_dfs;
    int[4] mcast_rate;
    struct ieee80211_ht_cap ht_capa;
    struct ieee80211_ht_cap ht_capa_mask;
    struct key_params * wep_keys;
    int wep_tx_key;
}
```
</details>
</li>
</ul>

## Differences
<b>Regular</b>
<ul>
<li>
No changes between <code>4.4.0-21-generic-amd64</code> and <code>4.8.0-22-generic-amd64</code> ✅
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
<details>
<summary>Changed between <code>4.15.0-20-generic-amd64</code> and <code>4.18.0-10-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field added. </b>
<code>bool control_port_over_nl80211</code>
</li>
<li>
<b>Field added. </b>
<code>struct key_params * wep_keys</code>
</li>
<li>
<b>Field added. </b>
<code>int wep_tx_key</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>4.18.0-10-generic-amd64</code> and <code>5.0.0-13-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.0.0-13-generic-amd64</code> and <code>5.3.0-18-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.3.0-18-generic-amd64</code> and <code>5.4.0-26-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int[3] mcast_rate</code> ➡️ <code>int[4] mcast_rate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.4.0-26-generic-amd64</code> and <code>5.8.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.8.0-25-generic-amd64</code> and <code>5.11.0-16-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int[4] mcast_rate</code> ➡️ <code>int[5] mcast_rate</code>
</li>
</ul>
</details>
</li>
<li>
No changes between <code>5.11.0-16-generic-amd64</code> and <code>5.13.0-19-generic-amd64</code> ✅
</li>
<li>
No changes between <code>5.13.0-19-generic-amd64</code> and <code>5.15.0-25-generic-amd64</code> ✅
</li>
<li>
<details>
<summary>Changed between <code>5.15.0-25-generic-amd64</code> and <code>5.19.0-21-generic-amd64</code> ❓</summary>
<ul>
<li>
<b>Field type changed. </b>
<code>int[5] mcast_rate</code> ➡️ <code>int[6] mcast_rate</code>
</li>
</ul>
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
