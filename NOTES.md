* Fastmail

- Published SPF record as [directed](https://www.fastmail.help/hc/en-us/articles/360060591153#dkim):
   - TXT record, value `v=spf1 include:spf.messagingengine.com ?all`
- Published DKIM records as selectors:
   - CNAME record name `fm1._domainkey`, value `fm1.rebeccathomas.com.dkim.fmhosted.com`
   - CNAME record name `fm2._domainkey`, value `fm2.rebeccathomas.com.dkim.fmhosted.com`
   - CNAME record name `fm3._domainkey`, value `fm3.rebeccathomas.com.dkim.fmhosted.com`
