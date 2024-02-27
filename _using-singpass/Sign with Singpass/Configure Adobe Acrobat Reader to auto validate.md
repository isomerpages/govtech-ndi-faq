---
title: Configure Adobe Acrobat Reader to auto validate
permalink: /using-singpass/sign-with-singpass/configure-adobe-auto-validate/
variant: tiptap
description: ""
third_nav_title: Sign with Singpass
---
<h3>How do I configure Adobe Acrobat Reader to automatically validate the digital signature generated using Sign with Singpass in a signed document?</h3>
<p>After ensuring that you have the latest Adobe Acrobat Reader installed,
follow these steps below to add the National Certificate Authority (NCA)
Root CA Cert to your Adobe Acrobat Reader’s list of trusted identities:
<br>
</p>
<ol data-tight="true" class="tight">
<li>
<p>Download the NCA Root CA Cert, “SNRCA-G1.fdf”, issued by the National
Certification Authority from <a href="https://www.nca.gov.sg/SNRCA-G1.fdf" rel="noopener noreferrer nofollow" target="_blank"><u>https://www.nca.gov.sg/SNRCA-G1.fdf</u><br></a>
</p>
</li>
<li>
<p>Open the downloaded “SNRCA-G1.fdf” file &gt; click “Set Contact Trust”
&gt; check “Use this certificate as a trusted root” &gt; click “OK” to
complete the one-time configuration.</p>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 50%;" height="auto" width="100%" alt="screenshot of the data exchange file, import contact feature" src="/images/sign_configure_adobe_1.png">
</div>
<p></p>
<div class="isomer-image-wrapper">
<img style="width: 50%;" height="auto" width="100%" alt="screenshot of the import contact settings feature" src="/images/sign_configure_adobe_2.png">
</div>
<p></p>
</li>
<li>
<p>Your Adobe Acrobat is now ready to automatically validate digital signature(s)
generated using Sign with Singpass.
<br>
</p>
</li>
<li>
<p>Refer to the Signature Validation Check notification at the top of the
document each time you wish to check the integrity of the signed document.</p>
</li>
</ol>
<p></p>