# AdaptiveBase for Claude

Your AI can coach you. AdaptiveBase remembers your training. Veteran owned.

This plugin adds the AdaptiveBase training skill and connects Claude to the
AdaptiveBase MCP server at `https://mcp.adaptivebase.app/plugin/mcp`. Claude
supplies the conversation and reasoning; AdaptiveBase stores your exercise
programs, workout history and confirmed training facts.

## What you can do

- Check today's workout, readiness and baseline assessments
- Log completed sets one at a time and finish a session
- Review strength progress and training trends
- Record reported sleep and recovery, and manage confirmed home or travel gym equipment
- Coaches: propose a program to an athlete who has consented; the athlete approves it in the portal

AdaptiveBase supports exercise planning and tracking. It does not diagnose
injuries, prescribe medical treatment, read Apple Health from a browser,
purchase equipment or book trainers.

## Use it

Install the plugin, then connect AdaptiveBase from the plugin's **Connectors**
tab and sign in. An AdaptiveBase account and active Connect access are required.
Ask Claude, for example, "What is my workout today?" or "Log 165 for 6 on bench".

## Data

The plugin sends only the requests you make (workout, recovery, equipment and
program details) to your AdaptiveBase account over HTTPS after you sign in with
OAuth. It stores nothing itself and contains no credentials. See the privacy
policy for retention and sharing.

## Help

- Support: https://adaptivebase.app/support
- Privacy: https://adaptivebase.app/privacy
- Terms: https://adaptivebase.app/terms

## Scope, license and trademarks

This repository is a published copy of the AdaptiveBase plugin package for
Claude. It is licensed under the [Apache License 2.0](LICENSE) (see also
[NOTICE](NOTICE)). Please read what that does and does not cover.

**What is licensed.** Only the files in this repository: the plugin manifest,
the MCP connection configuration, the training skill and its reference
documents, and this README. You may use, copy, modify and redistribute those
files under the terms of Apache-2.0.

**What is not licensed.**

- **The AdaptiveBase service.** The MCP server at `mcp.adaptivebase.app`, its
  API, tools, data, models, infrastructure, website and any content returned
  by them are not part of this package. Nothing here grants access to, or any
  right to use, copy, scrape, benchmark, resell or build a competing service
  from, the AdaptiveBase service. Access requires an AdaptiveBase account and
  an active Connect plan, and use is governed solely by the
  [Terms of Service](https://adaptivebase.app/terms) and the
  [Privacy Policy](https://adaptivebase.app/privacy). Those terms prevail over
  this license for any use of the service.
- **Trademarks and branding.** "AdaptiveBase", the AdaptiveBase name, logo,
  mountain mark, icons and tagline are trademarks of AdaptiveBase. Under
  Section 6 of the Apache License, no trademark rights are granted. You may
  use the name only to accurately describe the origin of this package, for
  example "based on the AdaptiveBase plugin". A modified copy must not use the
  AdaptiveBase name, logo or icons in a way that suggests it is the official
  plugin or is endorsed by AdaptiveBase, and must be renamed. The brand
  assets used by the official listing are not included in this repository.
- **User data.** Training, recovery, equipment and account data belong to the
  people who create them and are never licensed under this repository.

**No endorsement or affiliation.** Forks, redistributions and derivative works
are not affiliated with or endorsed by AdaptiveBase unless AdaptiveBase says so
in writing. Only the listing published by AdaptiveBase in the Claude directory
is the official plugin.

**Not medical advice.** AdaptiveBase supports exercise planning and tracking.
Nothing in this package, the skill text or the service's responses is medical
advice, a diagnosis, or a treatment recommendation. Consult a qualified
professional before starting or changing an exercise program, and stop and seek
care if you feel pain, dizziness or other symptoms. AI-generated suggestions can
be wrong.

**No warranty and limited liability.** As Sections 7 and 8 of the Apache
License state, this package is provided "AS IS", without warranties or
conditions of any kind, and AdaptiveBase is not liable for damages arising from
its use. Service-level commitments, if any, appear only in the Terms of
Service.

**Contributions.** This repository is generated automatically from a private
source repository, so changes made here are overwritten and pull requests are
not merged. Suggestions and bug reports are welcome through
[support](https://adaptivebase.app/support). Anything you submit to us is
licensed to AdaptiveBase under Section 5 of the Apache License unless you state
otherwise in writing.

**Security.** Report vulnerabilities privately to support@adaptivebase.app
rather than opening a public issue. Do not post credentials, tokens or personal
data in issues.
