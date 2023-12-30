# Startup Forge

Welcome to Startup Forge. This is an opinionated version of the information I wish I was told when building a startup. Knowing this advice would have saved me months of work, so I’d like to share it with you.

This resource is built for people with a technical background. In the beginning there is some non technical work, but I’ll mostly focus on building a good production ready tech stack. I won’t overly prioritize free software. When a paid service can save time at a reasonable price I’ll recommend it.

Continue Reading: [https://docs.startupforge.dev/ ](https://docs.startupforge.dev/)

<!--
# Old docs:

This is a guide about what I've learned creating a startup. Mostly the technical bits. Hopefully you find it helpful!

# Setup Domain & Email

- [ ] Come up with a name. It doesn't have to be perfect.
  - Check the name's availability to buy as a domain and on other sites like GitHub before proceeding too far.
- [ ] Buy the domain like `startupforge.dev`.
  - Register it under an account outside the domain, like startupforge@gmail.com, or a personal account.
  - [Namecheap](https://www.namecheap.com/) is a solid domain registrar, but there are plenty of other good options.
- [ ] Create a [Google workspace](https://workspace.google.com/) account with the new domain.
  - Follow Google's onboarding instructions to eventually setup the domain to receieve email. You will likely need to update TXT records to verify you own the domain, and MX records to route emails appropriately.
- [ ] Login to your email and make sure it works.

# Account Security

- [ ] Get a password manager like [Bitwarden](https://bitwarden.com/), or whichever you prefer.
- [ ] Make sure the account used with the domain registrar and Google workspaces is properly secure. They are the master keys to almost everything.

# Azure

This section and others will be setup to use Azure infrastructure. AWS and Google Cloud should have simmilar offerings.

- [ ] Create a [Microsoft account](https://signup.live.com/signup) with your new email.
- [ ] Login to Azure portal and setup your primary subscription with an appropriate name and spend limits.
- [ ] Login to Entra and update your [default domain](https://entra.microsoft.com/#view/Microsoft_AAD_IAM/DomainsList.ReactView).
  - (Verify your custom domain with a TXT record, and then update it to primary. Sometimes updating to primary fails, but if you refresh it might fix it.)

# Monorepo

- [ ] Setup github org.
-->
