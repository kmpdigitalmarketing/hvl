<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>HVL: CS Decision Matrix</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@600;700&family=IBM+Plex+Sans:wght@400;500;600&display=swap" rel="stylesheet">
<style>
:root{
  box-sizing:border-box;
  padding-top:env(safe-area-inset-top,0px);
  padding-bottom:env(safe-area-inset-bottom,0px);
  --bg:#F2F4F6; --surface:#FFFFFF; --ink:#18212B; --muted:#5B6773; --line:#D9DEE3;
  --amber:#E3A008; --amber-soft:#FFF4D6;
  --yes:#1E7A4C; --yes-soft:#E2F4EA; --no:#B3382C; --no-soft:#FBE8E5; --info:#2B5F9E; --info-soft:#E4EEF9;
  --head:'Bricolage Grotesque','Segoe UI',system-ui,sans-serif;
  --body:'IBM Plex Sans','Segoe UI',system-ui,sans-serif;
}
@media (prefers-color-scheme:dark){
  :root:not([data-theme="light"]){
    --bg:#12171D; --surface:#1B232C; --ink:#E8ECEF; --muted:#9AA6B2; --line:#2D3844;
    --amber:#F2B632; --amber-soft:#3A2F10;
    --yes:#58C28D; --yes-soft:#16342A; --no:#F08A7E; --no-soft:#3B1E1B; --info:#7FB0EB; --info-soft:#1B2E45;
  }
}
:root[data-theme="dark"]{
  --bg:#12171D; --surface:#1B232C; --ink:#E8ECEF; --muted:#9AA6B2; --line:#2D3844;
  --amber:#F2B632; --amber-soft:#3A2F10;
  --yes:#58C28D; --yes-soft:#16342A; --no:#F08A7E; --no-soft:#3B1E1B; --info:#7FB0EB; --info-soft:#1B2E45;
}
html{scroll-padding-top:calc(env(safe-area-inset-top,0px) + 72px);scroll-behavior:smooth}
*,*::before,*::after{box-sizing:inherit}
body{margin:0;background:var(--bg);color:var(--ink);font:400 16px/1.55 var(--body)}
a{color:var(--info)}
header.top{position:sticky;top:env(safe-area-inset-top,0px);z-index:5;background:var(--bg);border-bottom:1px solid var(--line)}
.bar{max-width:1080px;margin:0 auto;padding:10px 16px;display:flex;gap:12px;align-items:center;flex-wrap:wrap}
.bar h1{font:700 20px/1 var(--head);margin:0;margin-right:auto;display:flex;align-items:center;gap:8px}
.bar h1::before{content:"";width:12px;height:12px;border-radius:50%;background:var(--amber);box-shadow:0 0 0 4px var(--amber-soft)}
input[type=search]{font:inherit;padding:8px 12px;border:1px solid var(--line);border-radius:8px;background:var(--surface);color:var(--ink);min-width:200px;flex:1;max-width:320px}
input:focus-visible,a:focus-visible,button:focus-visible{outline:2px solid var(--info);outline-offset:2px}
nav.jump{max-width:1080px;margin:0 auto;padding:0 16px 10px;display:flex;gap:8px;overflow-x:auto}
nav.jump a{white-space:nowrap;text-decoration:none;color:var(--ink);border:1px solid var(--line);background:var(--surface);padding:5px 12px;border-radius:999px;font-size:14px;font-weight:500}
nav.jump a:hover{border-color:var(--amber)}
main{max-width:1080px;margin:0 auto;padding:20px 16px 64px}
.intro{color:var(--muted);max-width:68ch;margin:0 0 24px}
.legend{display:flex;gap:8px;flex-wrap:wrap;margin-bottom:24px;font-size:14px}
section.case{background:var(--surface);border:1px solid var(--line);border-radius:12px;margin-bottom:24px;overflow:hidden}
section.case>h2{font:700 22px/1.2 var(--head);margin:0;padding:18px 20px;border-bottom:1px solid var(--line)}
section.case>h2 small{display:block;font:400 14px/1.4 var(--body);color:var(--muted);margin-top:4px}
.scroll{overflow-x:auto}
table{border-collapse:collapse;width:100%;min-width:720px}
th,td{text-align:left;vertical-align:top;padding:12px 16px;border-bottom:1px solid var(--line);font-size:15px}
th{font-weight:600;color:var(--muted);font-size:13px;background:var(--bg)}
tr:last-child td{border-bottom:0}
td:first-child{width:26%;font-weight:500}
.tag{display:inline-block;font-size:13px;font-weight:600;padding:1px 9px;border-radius:6px;margin-right:6px;white-space:nowrap}
.yes{background:var(--yes-soft);color:var(--yes)} .no{background:var(--no-soft);color:var(--no)} .info{background:var(--info-soft);color:var(--info)} .warn{background:var(--amber-soft);color:var(--ink)}
ul{margin:0;padding-left:18px} li{margin:2px 0}
.note{margin:0;padding:14px 20px;background:var(--amber-soft);border-top:1px solid var(--line);font-size:15px}
.note b{font-weight:600}
code{font:500 13px ui-monospace,Menlo,monospace;background:var(--bg);padding:1px 6px;border-radius:4px}
.empty{display:none;text-align:center;color:var(--muted);padding:40px 0}
@media (max-width:600px){h1{font-size:18px}.bar h1{width:100%}}
@media (prefers-reduced-motion:reduce){html{scroll-behavior:auto}}
</style>
</head>
<body>
<header class="top">
  <div class="bar">
    <h1>HVL: CS decision matrix</h1>
    <input type="search" id="q" placeholder="Search a scenario or keyword" aria-label="Search scenarios">
  </div>
  <nav class="jump" aria-label="Scenarios">
    <a href="#cancel">Cancellation</a>
    <a href="#damage">Damaged / defective</a>
    <a href="#inquiry">Product inquiry</a>
    <a href="#received">Received product</a>
    <a href="#returns">Returns &amp; misc</a>
    <a href="#outbound">Outbound</a>
  </nav>
</header>

<main>
  <p class="intro">Find the scenario, answer the question in the first column, then follow the action. Always acknowledge the customer first, then work the case. Tag the <b>store manager</b> when a case needs approval or an offer decision. SP = Shopify, HS = Helpscout, WFTU = waiting for tracking update.</p>
  <div class="legend">
    <span class="tag yes">YES</span><span class="tag no">NO</span><span class="tag info">Internal</span><span class="tag warn">Customer reply</span>
  </div>

  <section class="case" id="cancel" data-s="cancellation cancel hold 24h refund store credit dispute wftu discount">
    <h2>Cancellation<small>Customer asks to cancel an order</small></h2>
    <div class="scroll"><table>
      <thead><tr><th>Question</th><th>Internal action</th><th>Tell the customer</th></tr></thead>
      <tbody>
      <tr><td><span class="tag yes">YES</span>Order placed within 24H?</td>
        <td><ul><li>HOLD the shipment: send a Slack message</li><li>Snooze the ticket to the next day</li><li>Add a note in SP with the Slack link for reference</li></ul></td>
        <td>Acknowledge first. Say we are checking whether cancellation is still possible.</td></tr>
      <tr><td><span class="tag no">NO</span>Order older than 24H?</td>
        <td>No hold. Get the HVL tracking #.</td>
        <td>Explain that cancellation is no longer possible and send the HVL tracking #.</td></tr>
      <tr><td>Hold was successful?</td>
        <td><ul><li>Offer either <b>10% discount</b> as partial refund, or <b>120% store credit</b></li></ul></td>
        <td>Present both options and ask which they prefer.</td></tr>
      <tr><td>Customer accepts the offer</td>
        <td><ul><li><span class="tag info">Processing</span>Cancel in SP</li><li><span class="tag info">WFTU</span>Open a dispute in SP, then refund</li><li>Confirm the order is refunded or cancelled in SP <b>before</b> adding it to the refund approval case (10%)</li><li>Document the cancellation</li><li>Once approval comes through, refund the customer</li></ul></td>
        <td>Confirm the outcome and timeline.</td></tr>
      <tr><td>Customer complains or pushes back</td>
        <td><ul><li>Create a note</li><li>Tag the <b>store manager</b> and ask what we can offer, or give a one-line summary of the customer's argument (keep it simple)</li></ul></td>
        <td>Acknowledge and hold while the store manager replies.</td></tr>
      </tbody>
    </table></div>
  </section>

  <section class="case" id="damage" data-s="damaged defective quality photo video resend replacement refund eod manager multiple orders">
    <h2>Damaged or defective item received<small>Check for proof first</small></h2>
    <div class="scroll"><table>
      <thead><tr><th>Question</th><th>Internal action</th><th>Tell the customer</th></tr></thead>
      <tbody>
      <tr><td><span class="tag yes">YES</span>Customer sent photos or videos?</td>
        <td><ul><li>Add to the <b>Quality issue</b> tab</li><li>Include in the EOD report</li></ul></td>
        <td>Apologize. Offer a <b>FREE resend</b> right away. No need to keep the lamp.</td></tr>
      <tr><td><span class="tag yes">YES</span> but customer rejects the resend</td>
        <td><ul><li>Add a note and tag the <b>store manager</b>: ask if there is another option to offer</li><li>Add to the quality sheet</li><li>Ask for a refund in SP</li><li>Snooze to the next day</li></ul></td>
        <td>Acknowledge, say we are reviewing other options.</td></tr>
      <tr><td><span class="tag no">NO</span>No photos or proof sent?</td>
        <td>Wait for proof before escalating.</td>
        <td>Ask for photos or videos. Even if blurry, ask for clearer ones. Explain we need them to escalate the case, that a replacement is sent once damage is verified, and that they do not need to keep the item.</td></tr>
      <tr><td>Customer has multiple orders</td>
        <td>Clarify which item is damaged. Replace only that item.</td>
        <td>Ask which item has the damage.</td></tr>
      </tbody>
    </table></div>
    <p class="note"><b>Escalation:</b> if the customer stays firm, tag the <b>store manager</b>. Keep the message one line with context; bullets only if needed. If SP is slow to respond (an answer should come within 24 hrs), ask for help in Slack and mention that a dispute was opened in SP.</p>
  </section>

  <section class="case" id="inquiry" data-s="product inquiry slack helpscout question">
    <h2>Product inquiry<small>Customer asks about a product</small></h2>
    <div class="scroll"><table>
      <thead><tr><th>Question</th><th>Internal action</th><th>Tell the customer</th></tr></thead>
      <tbody>
      <tr><td><span class="tag yes">YES</span>Slack already has a chat for this product?</td>
        <td>Search Slack using the <b>product name in English</b>. Copy all the info there; it may already answer the concern.</td>
        <td>Acknowledge, then reply with the info.</td></tr>
      <tr><td><span class="tag no">NO</span>Nothing in Slack yet?</td>
        <td>Ask in the product questions Slack channel. Add the Slack link in HS so the thread is easy to find again.</td>
        <td>Acknowledge first and say we are confirming.</td></tr>
      </tbody>
    </table></div>
  </section>

  <section class="case" id="received" data-s="received product longer cable different lamp custom order approval b2b supplier draft orders replacement eur">
    <h2>Inquiry about an already received product<small>Needs a longer cable, a different lamp, etc.</small></h2>
    <div class="scroll"><table>
      <thead><tr><th>Question</th><th>Internal action</th><th>Tell the customer</th></tr></thead>
      <tbody>
      <tr><td>Customer needs an add-on or different item</td>
        <td><ul><li>Ask in Slack in the order issues Slack channel, tag the assigned teammates</li><li>Include: order #, product, what the customer needs, and the cost</li><li>Add the Slack link to HS</li></ul></td>
        <td>Acknowledge first.</td></tr>
      <tr><td>Quote is ready: does it need Manager approval?</td>
        <td>Check the table below. If no approval is needed, create a <b>CUSTOM ORDER</b> in SP, link the Slack convo with the supplier, and document it in the <b>DRAFT orders</b> tab. Monitor every 2-3 days until tracking exists.</td>
        <td>Item is free of charge. Send the new tracking once available.</td></tr>
      <tr><td>B2B (bulk or corporate order)</td>
        <td>Tag the B2B team.</td>
        <td>Acknowledge.</td></tr>
      </tbody>
    </table></div>
    <div class="scroll"><table style="min-width:520px">
      <thead><tr><th>Original order value</th><th>Cost of the extra or replacement part</th><th>Manager approval?</th></tr></thead>
      <tbody>
        <tr><td>Up to 200 EUR</td><td>Up to 15 EUR</td><td><span class="tag yes">Not needed</span>Create the custom order right away</td></tr>
        <tr><td>200 to 500 EUR</td><td>Up to 40 EUR</td><td><span class="tag yes">Not needed</span>Create the custom order right away</td></tr>
        <tr><td>Anything above these limits</td><td>More than the limit for that order value</td><td><span class="tag no">Needed</span>Tag the store manager and ask how much to charge. Always include the supplier's quote.</td></tr>
      </tbody>
    </table></div>
    <p class="note"><b>Reminder:</b> when approval is needed, one line to the store manager with the order #, the part, and the supplier quote. Never leave out the quote.</p>
  </section>

  <section class="case" id="returns" data-s="return change of mind partial refund store credit website match color china escalate">
    <h2>Returns and other special cases</h2>
    <div class="scroll"><table>
      <thead><tr><th>Scenario</th><th>Internal action</th><th>Tell the customer</th></tr></thead>
      <tbody>
      <tr><td>Wants to return: change of mind, won't send photos</td>
        <td>Normal workflow: <b>20% partial refund</b> or <b>30% store credit</b>. Attach the form.</td>
        <td>Offer both options.</td></tr>
      <tr><td>Wants to return: "doesn't match the website"</td>
        <td>Ask for a photo to compare. If it is only a color difference, proceed with the normal workflow above.</td>
        <td>Politely explain that the difference is due to color.</td></tr>
      <tr><td>Asks if the product comes from China</td>
        <td>Escalate in the Slack channel (the private escalation channel).</td>
        <td><span class="tag no">Do not respond</span></td></tr>
      </tbody>
    </table></div>
  </section>

  <section class="case" id="outbound" data-s="outbound return request address error loox reviews">
    <h2>Outbound cases<small>These follow the shared SOP document</small></h2>
    <div class="scroll"><table>
      <thead><tr><th>Scenario</th><th>Action</th></tr></thead>
      <tbody>
      <tr><td>Return request (outbound)</td><td rowspan="3">Follow the internal outbound SOP document.</td></tr>
      <tr><td>Address error (outbound)</td></tr>
      <tr><td>Loox reviews (outbound)</td></tr>
      </tbody>
    </table></div>
  </section>

  <p class="empty" id="empty">No scenario matches that search.</p>
</main>

<script>
(function(){
  var q=document.getElementById('q'),cards=[].slice.call(document.querySelectorAll('section.case')),empty=document.getElementById('empty');
  q.addEventListener('input',function(){
    var v=q.value.trim().toLowerCase(),shown=0;
    cards.forEach(function(c){
      var hit=!v||(c.dataset.s+' '+c.textContent).toLowerCase().indexOf(v)>-1;
      c.style.display=hit?'':'none'; if(hit)shown++;
    });
    empty.style.display=shown?'none':'block';
  });
})();
</script>
</body>
</html>
