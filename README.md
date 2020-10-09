[![license](https://img.shields.io/github/license/mashape/apistatus.svg?maxAge=2592000)](https://opensource.org/licenses/MIT)

# check_mk_whoswap

Simple Check_MK check to view who's using swap with Long output 'multiline'.

## Install

### Check_MK CRE (check-mk-raw)

Download `custom/gitlab_runner/lib/local/whoswap` and copy
to `/usr/lib/check_mk_agent/local/` directory.

### Check_MK CEE (check-mk-enterprise)

The package can be distributed with [Agent Backery](https://checkmk.com/cms_wato_monitoringagents.html)

* Download [latest release](https://github.com/zionio/check_mk_whoswap/releases)
and upload with [Extension Packages](https://checkmk.com/cms_mkps.html)
* Go to _Monitoring Agents_ -> _Rules_ -> _Generic Options_ -> _Deploy custom files with agent_
and create (or edit) a Rule.
* Bake Agents (don't forget to sign all agents)
