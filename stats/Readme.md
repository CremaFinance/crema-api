# Stats(v1)

## swap stats
<a id=swapstats1528> </a>
### General

**Host:** https://api.crema.finance

**Path:** /v1/swap/count

**Method:** GET

**Endpoints Description:**


### Request Parameters

### Return Data
<table> 
<thead class="ant-table-thead"> 
<tr> 
 <th key="name">Name</th>
 <th key="type">Type</th>
 <th key="required">Compulsory</th>
 <th key="default">Default value</th>
 <th key="desc">Description</th>
 <th key="sub">Other</th> 
</tr> 
</thead>
<tbody classname="ant-table-tbody">
<tr key="0-0">
 <td key="0"><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> req_id</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">Optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap"></span></td>
 <td key="5"></td>
</tr>
<tr key="0-1">
 <td key="0"><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> code</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">Optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">"OK" means that request succeeds</span></td>
 <td key="5"></td>
</tr>
<tr key="0-2">
 <td key="0"><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> msg</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">Optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">if message is requested successfully:Success</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3">
 <td key="0"><span style="padding-left: 0px"><span style="color: #8c8a8a"></span> data</span></td>
 <td key="1"><span>object</span></td>
 <td key="2">Optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">request to return data</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-0">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tvl_in_usd</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total TVL(all pools)</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-1">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> vol_in_usd_24h</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Latest 24h VOL(all pools)</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-2">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tx_num_24h</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Latest 24h number of transactions(all pools)</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-3">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> vol_in_usd</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total cumulative VOL(all pools)</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-4">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tx_num</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total cumulative number of transactions(all pools)</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-5">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> user_num</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">number of users(all pools)</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-6">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> token_num</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">number of token(all pools)</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> pools</span></td>
 <td key="1"><span>object []</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Pool list</span></td>
 <td key="5"><p key="3"><span style="font-weight: '700'">item type: </span><span>object</span></p></td>
</tr>
<tr key="0-3-7-0">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> name</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">optional</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Pool name</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-1">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tvl_in_usd</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total TVL</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-2">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> vol_in_usd_24h</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Latest 24h VOL</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-3">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tx_num_24h</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Latest 24h number of transactions</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-4">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> apr</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">apr</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-5">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> swap_account</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">swap account</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-6">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tx_num</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total number of transactions</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-7">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> vol_in_usd</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total VOL</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-8">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> price_intervals</span></td>
 <td key="1"><span>object</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap"></span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-8-0">
 <td key="0"><span style="padding-left: 60px"><span style="color: #8c8a8a">├─</span> upper_price</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Recommended max price</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-8-1">
 <td key="0"><span style="padding-left: 60px"><span style="color: #8c8a8a">├─</span> lower_price</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Recommended min price</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-9">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> price</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">price</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-10">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> price_rate_24h</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">24h price change</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-11">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> token_a_reserves</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">The reserves of token A in the pool</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-7-11">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> token_b_reserves</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">The reserves of token B in the pool</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8">
 <td key="0"><span style="padding-left: 20px"><span style="color: #8c8a8a">├─</span> tokens</span></td>
 <td key="1"><span>object []</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">token list</span></td>
 <td key="5"><p key="3"><span style="font-weight: '700'">item type: </span><span>object</span></p></td>
</tr>
<tr key="0-3-8-0">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> name</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">token name</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8-1">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tvl_in_usd</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total TVL</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8-2">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> vol_in_usd_24h</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Latest 24h VOL</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8-3">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tx_num_24h</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Latest 24h number of transactions</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8-4">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> tx_num</span></td>
 <td key="1"><span>number</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total cumulative number of transactons</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8-5">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> vol_in_usd</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">Total VOL</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8-6">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> price</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">price</span></td>
 <td key="5"></td>
</tr>
<tr key="0-3-8-7">
 <td key="0"><span style="padding-left: 40px"><span style="color: #8c8a8a">├─</span> price_rate_24h</span></td>
 <td key="1"><span>string</span></td>
 <td key="2">compulsory</td>
 <td key="3"></td>
 <td key="4"><span style="white-space: pre-wrap">24h price change</span></td>
 <td key="5"></td>
</tr> 
</tbody> 
</table>
   
            