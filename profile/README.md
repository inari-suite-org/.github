<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/inari-suite-org/.github/main/profile/assets/banner-dark.svg">
    <img src="https://raw.githubusercontent.com/inari-suite-org/.github/main/profile/assets/banner-light.svg" alt="Inari Suite. Security tools for FiveM servers." width="100%">
  </picture>
</p>

Inari Suite writes open-source security tools for FiveM server administrators. Each tool does one job and says
plainly what it does not cover.

## Tools

<a href="https://github.com/inari-suite-org/torii-fx">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/inari-suite-org/.github/main/profile/assets/card-torii-dark.svg">
    <img src="https://raw.githubusercontent.com/inari-suite-org/.github/main/profile/assets/card-torii-light.svg" alt="torii: runtime permission firewall for server-side Lua resources. v0.1 alpha, MIT." width="100%">
  </picture>
</a>

<br>

**torii** gives every resource a short list of permissions (which hosts it may call, whether it may run dynamic
code) and enforces them while the server runs. It starts in observe mode, so you can install it on a live server
before you block anything.

## How we build

- **Least privilege, not signatures.** We do not try to recognise bad code. We control what code is allowed to do.
- **Observe, then enforce.** Every tool reports before it blocks.
- **Limits in writing.** Each repository publishes a threat model: what the tool stops, what it only reports, and what it cannot see.
- **Few dependencies.** The torii command line tool has none.

## The name

Inari is the Shinto kami of rice and prosperity, and her messengers are foxes. Her shrines are the ones lined with
torii gates. The suite follows that vocabulary: one name per part of a shrine, one job per tool.

| Name | Meaning | Job | State |
|---|---|---|---|
| torii | the gate | runtime permission firewall for Lua resources | v0.1 alpha |
| shimenawa | the rope that marks a protected boundary | resource sandboxing | idea |
| ofuda | a protective talisman | secrets and license scanning | idea |
| komainu | the guardian pair at the gate | monitoring and alerting | idea |
| sekisho | a checkpoint | network egress policy | idea |

"Idea" means a name and a sentence. Nothing is built yet.

## Report a problem

A way around one of our tools is a vulnerability. Report it privately from the repository's **Security** tab
("Report a vulnerability"). For every bypass we fix, we add a test that fails without the fix.

<p align="center">
  <br>
  <img src="https://raw.githubusercontent.com/inari-suite-org/.github/main/profile/assets/logo/inari-kitsune-transparent.svg" alt="" width="84">
</p>
