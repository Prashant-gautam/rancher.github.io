---
title: API
layout: rancher-default
version: latest
lang: en
---

## healthcheckInstanceHostMap



### Resource Fields

Field | Type | Create | Update | Default | Notes
---|---|---|---|---|---
description | string | Optional | Yes | - | 
healthState | string | - | - | - | 
hostId | [host]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/host/) | - | - | - | The unique identifier for the associated host
id | int | - | - | - | The unique identifier for the healthcheckInstanceHostMap
instanceId | [instance]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/api-resources/instance/) | - | - | - | The unique identifier for the associated instance
name | string | Optional | Yes | - | 


Please read more about the [common resource fields]({{site.baseurl}}/rancher/{{page.version}}/{{page.lang}}/api/common/). 
These fields are read only and applicable to almost every resource. We have segregated them from the list above.








### Actions

<div class="action">
<span class="header">
remove
<span class="headerright">POST:  <code>${actions.remove}</code></span></span>
<div class="action-contents">
To remove the healthcheckInstanceHostMap
<br>

<span class="input">
<strong>Input:</strong>This action has no inputs</span>
<br>

<br>


<span class="output"><strong>Output:</strong> An updated copy of the <a href="/rancher/api/api-resources/healthcheckInstanceHostMap/">healthcheckInstanceHostMap</a> resource</span>
</div>
</div>

