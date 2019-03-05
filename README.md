# labs.learn.study

## How to use

Edit the `hosts` inventory file to contain the hostname or IP of a minimal Fedora 29 Server, and then run:

    ansible-playbook -i hosts --become --ask-become-pass playbooks/all.yaml

This will install OpenShift v4 using the [openshift installer](https://github.com/openshift/installer).

The Installation log is in /opt/openshift-install.run/.openshift_install.log on your server.

If you have trouble, refer to [the troubleshooting guide](https://github.com/openshift/installer/blob/master/docs/user/troubleshooting.md).

The installation will take at least tens of minutes, depending on your hardware.

## How to develop

    ansible-playbook --syntax-check playbook.yaml

## Blah

Learn how to #DataCenter #Virtualization #SDN #Monitoring #CloudNative #AppDev #Storage #Containers #Federation ...

Labs, not a singleton ab - you can, and should, run everything here for yourself.

Open - you can look at and web login to our public instances.

On Premise - at "home" on bare metal (typically; but not exclusive, also usable on a Public Cloud provider).

Primarily focused on using open source project supported by Red Hat, or of potential future interest (but not a hard rule).

Recipes - ready to run, not (only) words in blog posts.   But also ;) blogging, cross-posting to relevant community's blogs.

DevProd - when you run "like production", it makes it more real.  We have fun by monitoring each other's uptime!

## Principles

Script and automate everything, run anything from Git in CI/CD, only.

Containerize everything.  Literally.  No exceptions.

Monitor everything, using Prometheus and Grafana.

## To Do (and what's Done)

see [TODO.txt](TODO.txt) & [done.txt](done.txt)
