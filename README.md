<!--
https://www.arclab.com/en/kb/htmlcss/how-to-copy-text-from-html-element-to-clipboard.html
-->
<script>
function CopyToClipboard(id){
  var r = document.createRange();
  r.selectNode(document.getElementById(id));
  window.getSelection().removeAllRanges();
  window.getSelection().addRange(r);
  document.execCommand('copy');
  window.getSelection().removeAllRanges();
  return false;
}
</script>
# How to Donate
If you want to make a donation to Basement-Science, this document lists all currently available ways to do so.

Any amount is appreciated.

## Donate Cryptocurrency
Cryptocurrency is available globally and with mostly very low fees, and can respect everyone's privacy. 
It is currently the only supported way of donating.

Simply send any amount to the respective currency's address:
| Currency Name | Symbol | Address |
|:------------- |:------:|:------- |
| Bitcon | BTC | <a href="javascript:void(0);" onclick="CopyToClipboard('BTC');">&#x2398;</a>&nbsp;<span id="BTC">bc1qs06lfxq8qu92gx6y65ttckp0gv66acyeufnjr8</span> |
| Ethereum<br>(+ERC20) | ETH,<br>ETC | <a href="javascript:void(0);" onclick="CopyToClipboard('ETH');">&#x2398;</a>&nbsp;<span id="ETH">0xd484d7835f5555387d256bd059d6424d4491b0e4</span> |
| Monero | XMR | <a href="javascript:void(0);" onclick="CopyToClipboard('XMR');">&#x2398;</a>&nbsp;<span id="XMR">84Pk6a6FQQxEn4JXrTEgR8VhQULmvwLxh1wfmeua2SeaCcNwdyoXG3YcjiMcKVgXfihBrW3ZvK4PG3EnbqdyhFECETBtxms</span> |
