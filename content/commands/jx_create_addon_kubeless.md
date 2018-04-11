---
date: 2018-04-11T14:36:36Z
title: "jx create addon kubeless"
slug: jx_create_addon_kubeless
url: /commands/jx_create_addon_kubeless/
---
## jx create addon kubeless

Create a kubeless addon for hosting git repositories

### Synopsis

Creates the kubeless addon for serverless on kubernetes

```
jx create addon kubeless [flags]
```

### Examples

```
  # Create the kubeless addon in the kubeless namespace
  jx create addon kubeless
  
  # Create the kubeless addon in a custom namespace
  jx create addon kubeless -n mynamespace
```

### Options

```
  -b, --batch-mode         In batch mode the command never prompts for user input
  -c, --chart string       The name of the chart to use (default "incubator/kubeless")
      --headless           Enable headless operation if using browser automation
      --helm-update        Should we run helm update first to ensure we use the latest version (default true)
  -h, --help               help for kubeless
  -n, --namespace string   The Namespace to install into (default "kubeless")
      --no-brew            Disables the use of brew on MacOS to install or upgrade command line dependencies
  -r, --release string     The chart release name (default "kubeless")
      --verbose            Enable verbose logging
  -v, --version string     The version of the kubeless addon to use
```

### SEE ALSO

* [jx create addon](/commands/jx_create_addon/)	 - Creates an addon

###### Auto generated by spf13/cobra on 11-Apr-2018