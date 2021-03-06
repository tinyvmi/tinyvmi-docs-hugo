+++
title = "Step by Step"
description = ""
weight = 3
alwaysopen = true
toc = true

+++

Here is an overview of all steps we need to build and run TinyVMI. The following will introduce all the changes to the original Xen-4.10.0 source code in order to run TinyVMI:

1. [Install Xen with XSM FLASK Enabled]({{<relref "step-by-step/install-xen-with-flask.md" >}}).

2. [Configure TinyVMI]({{<relref "step-by-step/configuration">}})

    a) [Update XSM FLASK Policy]({{< relref "step-by-step/configuration/update-xsm-flask-policy.md" >}})

    b) [Update Stubdom Makefile]({{< relref "step-by-step/configuration/update-stubdom-makefile.md" >}})

    c) [Update Mini-OS Makefile]({{< relref "step-by-step/configuration/update-minios-makefile.md" >}})

    d) [Get Target Guest Kernel Info (Linux)]({{< relref "step-by-step/configuration/get-target-guest-info-linux.md" >}})

    e) [Configure TinyVMI with Target Guest Info]({{< relref "step-by-step/configuration/configure-tinyvmi-with-target-guest-info.md" >}})

3. [Build and Run TinyVMI]({{<relref "step-by-step/run-tinyvmi.md">}})